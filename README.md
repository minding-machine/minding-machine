# Minding-Machine
A machine that attentively gives heed to in order to obey.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Mind the instructions, machine." \
  | uvx minding-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install minding-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
minding-machine -a multilogue.txt
```
Or:
```bash
minding-machine multilogue.txt > response.txt
```
Or:
```bash
minding-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import minding_machine
```
