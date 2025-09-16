# MODULE 5: STRUCTURED DATA FOR DOCS

#### Use Python scripts to read write, and validate structured data formats like JSON and YAML.

#### Create a New Python File

1. In VS Code, click File > Open Folder, and create/select a folder like python-course
2. In the Explorer tab (left sidebar), click New File and name it: **data_checker.py**


#### Practice the following automations

Type the following text into the terminal and observe the automation.

| AUTOMATION                       | CODE                                                         |
| -------------------------------- | ------------------------------------------------------------ |
| Read a JSON file                 | import json<br/><br/>with open("config.json") as f:<br/>    config = json.load(f)<br/>    print(config["project_name"]) |
| Write a JSON file                | data = {"title": "API Guide", "version": "1.2"}<br/>with open("output.json", "w") as f:<br/>    json.dump(data, f, indent=2) |
| (Optional) Read YAML             | pip install pyyaml<br/><br/><br/>required = ["title", "version"]<br/>for key in required:<br/>    if key not in data:<br/>        print(f"Missing: {key}") |
| Validate keys in structured data | required = ["title", "version"]<br/>for key in required:<br/>    if key not in data:<br/>        print(f"Missing: {key}") |
