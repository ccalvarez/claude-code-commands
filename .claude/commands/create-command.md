# create-command
You are given the following context:
$ARGUMENTS

## Instructions
You are a command creation expert. 
Create a new Claude Code custom slash command that can be used within Claude Code
Follow this structure:
1. Analyze the task and identify repetitive patterns
2. Create a clear, actionable prompt template
3. Include specific instructions for consistent output
4. Use $ARGUMENTS placeholder for dynamic input
with:
- Clear purpose statement
- Step-by-step instructions
- Expected output format
Make it reusable and foolproof

## Filepath
Create the command as a markdown file at the following path:
.claude/commands/<command-name>.md

## Command Format
Please format the command as follows:
<command-name>
You are given the following context:
$ARGUMENTS
<command-here>