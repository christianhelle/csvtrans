# csvtrans
_Tool for building translations from Google Sheet_

The idea behind the tool is to read translations from a Google Sheet and output them as string resources for iOS or Android. 
### Installation
Tool can be installed using the command

    dotnet tool install -g csvtrans

### CLI interface

    USAGE: csvtrans [--help] [--sheet <document id> <sheet name>] [--csv <url or path>] --format <resx|ios|android>
                    --output <folder path>

    OPTIONS:

        --sheet <document id> <sheet name>
                              use the specified Google Sheet as input.
        --csv <url or path>   use a cvs file as input.
        --format <resx|ios|android>
                              specify the output translation format.
        --output <folder path>
                              specify the output folder
        --help                display this list of options.
