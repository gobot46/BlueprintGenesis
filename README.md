# BlueprintGenesis
BlueprintGenesis is an automation tool that comes the power of Smartsheet and OpenAI to automatically create and populate a set of sheets with AI-Generated Data, with the intention of Building Control Center Source Folder Templates

## Description
BlueprintGenesis helps you quickly setup up structured Smartsheet sheets with appropriate columns and sample data.

BlueprintGenesis helps you quickly set up structured Smartsheet "Source Folder" commonly referred to as the toolkit for a Control Center program's blueprint.
* Target a Folder in a workspace
* Uses AI to generate 5 sheets
* Updates each sheet's column structues based on a use case's project need's (For example, each sheet would have contest such as 1. Project Plan, 2. Budget, 3. Risk Log, 4. Team Roster, 5. Meeting Minutes)
* Generates realistic sample data based on your description/prompt
* Populates the sheet with the generated data

## Requirements
* Python 3.7 or higher
* smartsheet-python-sdk
* openai

## Installation
pip install smartsheet-python-sdk openai

## Environmental Variables
You'll need to set the following variables:
* OPENAI_API_KEY - Your OpenAI API Key
* SMARTSHEET_API_KEY - Your Smartsheet API key

## Usage
Run the script
