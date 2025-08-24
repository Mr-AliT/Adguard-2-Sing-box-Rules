# Adguard-2-Sing-box-Rules
Convert Adguard (TXT) rule to Sing-box Rules (SRS), Used In Nekobox, Karing and...Sing-box VPN Clients 

Adguard 2 Sing-box Rules

im used Sing-box windows v to Convert rules

sing-box rule-set convert --help

Usage:
  sing-box rule-set convert [source-path] [flags]

Flags:
  -h, --help            help for convert
  -o, --output string   Output file (default "<file_name>.srs")
  -t, --type string     Source type, available: adguard

Global Flags:
  -c, --config stringArray             set configuration file path
  -C, --config-directory stringArray   set configuration directory path
  -D, --directory string               set working directory
      --disable-color                  disable color output

So you Can Use Adguard Txt format Rules To Generate Sing-box SRS Rules

Use: sing-box rule-set convert --type adguard [--output <file-name>.srs] <file-name>.txt 
to convert to binary rule-set.
