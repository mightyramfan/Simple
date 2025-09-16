# MODULE 5: WORKING WITH FILES AND TEXT

#### Practice using Python scripts to read and write files like .txt and .md.

#### Create a New Python File

1. In VS Code, click File > Open Folder, and create/select a folder like python-course
2. In the Explorer tab (left sidebar), click New File and name it: **file_editor.py**


#### Practice the following automations

Type the following text into the terminal and observe the automation.

| AUTOMATION                         | CODE                                                         |
| ---------------------------------- | ------------------------------------------------------------ |
| Read a Markdown file               | with open("example.md", "r", encoding="utf-8") as f:<br/>    content = f.read()<br/>    print(content) |
| Write to a new file                | with open("summary.md", "w", encoding="utf-8") as f:<br/>    f.write("# Documentation Summary\n\nWritten with Python!") |
| Search and replace in file content | content = content.replace("outdated_term", "updated_term")   |
| Loop through multiple files        | import os<br/><br/>for filename in os.listdir("docs"):<br/>    if filename.endswith(".md"):<br/>        print("Found file:", filename) |
