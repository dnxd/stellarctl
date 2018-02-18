## stellarctl account generate mnemonic

generate account keys from a mnemonic passphrase (sep-0005)

### Synopsis


generate account keys from a mnemonic passphrase (sep-0005)

```
stellarctl account generate mnemonic [flags]
```

### Options

```
      --count int         number of accounts to generate from the mnemonic (default 1)
      --entropy int       size of entropy when generating a new mnemonic (default 256)
  -h, --help              help for mnemonic
      --mnemonic string   your mnemonic words
      --password string   password for the accounts
```

### Options inherited from parent commands

```
      --config string   config file (default is $HOME/.stellarctl.yaml)
      --format string   output format (default "yaml")
      --testnet         use the testnet
```

### SEE ALSO
* [stellarctl account generate](stellarctl_account_generate.md)	 - generate account keys

###### Auto generated by spf13/cobra on 18-Feb-2018