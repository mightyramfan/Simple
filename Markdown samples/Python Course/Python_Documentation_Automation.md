# MODULE 6: AUTOMATING DOCUMENTATION TASKS

#### Use Python to simplify and speed up repetitive doc tasks.

#### Create a New Python File

1. In VS Code, click File > Open Folder, and create/select a folder like python-course
2. In the Explorer tab (left sidebar), click New File and name it: **doc_automation.py**


#### Practice the following automations

Type the following text into the terminal and observe the automation.

| AUTOMATION                           | CODE                                                         |
| ------------------------------------ | ------------------------------------------------------------ |
| Generate a changelog from a list     | changes = ["Fixed typos", "Updated API section", "Added new diagrams"]<br/>with open("CHANGELOG.md", "w") as f:<br/>    for change in changes:<br/>        f.write(f"- {change}\n") |
| Convert `.txt` to `.md`              | with open("draft.txt") as fin:<br/>    text = fin.read()<br/><br/>with open("draft.md", "w") as fout:<br/>    fout.write("# Converted File\n\n" + text) |
| Pull data from a mock API (bonus)    | import requests<br/><br/>response = requests.get("https://jsonplaceholder.typicode.com/posts/1")<br/>data = response.json()<br/>print(data["title"]) |
| Auto-generate Markdown documentation | doc = f"# {data['title']}\n\n{data['body']}"<br/>with open("api_doc.md", "w") as f:<br/>    f.write(doc) |
