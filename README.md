# functions-cli-bin

This CLI allows users to interact with Segment Source Functions without using the REST API directly. 

## Install

### Mac and Linux 

```
curl -sf https://raw.githubusercontent.com/segmentio/functions-cli-bin/master/install.sh | sh
```

### Windows 

Download the binary at https://github.com/segmentio/functions-cli-bin/releases


## Usage

```bash
Usage:
  source-functions-cli [command]

Available Commands:
  auth        Acquire an API token
  help        Help about any command
  logs        Fetch logs for a source function between a specified time duration
  upload      register a function with a Segment source
  version     The client version

Flags:
  -u, --base-url string   Segment API base URL (default "https://platform.segmentapis.com")
  -h, --help              help for source-functions-cli

Use "source-functions-cli [command] --help" for more information about a command.
```
