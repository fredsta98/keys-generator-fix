# Keys.lol generator
This repository contains the key generator for [Keys.lol](https://keys.lol) from [keys-generator repo](https://github.com/SjorsO/keys-generator)

## Building and installing
1. Navigate to `C:\Users\USER\go\src` e.g `C:\Users\bob\go\src`
2. `git clone https://github.com/fredsta98/keys-generator-fix.git`
3. `cd keys-generator-fix`
4. install required packages with `go get`
5. build the executable with `go build`
6. Additionally you can build cross platform with the following commands:
	Windows:
		`GOOS=windows GOARCH=amd64 go build -o keys-generator-windows-128-amd64.exe`
		
	Linux:
		`GOOS=linux GOARCH=amd64 go build -o keys-generator-linux-amd64`
		
	MacOS:
		`GOOS=darwin GOARCH=amd64 go build -o keys-generator-mac-amd64-darwin`

## Usage

### Windows

1) Copy the directory path to your compiled program.
2) Add it to PATH via Control Panel.
3) Open a command prompt anywhere and run the commands below at Generating Keys.

### Linux

1) `sudo cp keys-generator-linux-amd64 /usr/local/bin`
2) `chmod +rwx /usr/local/bin/keys-generator-linux-amd64`
3) Open a terminal anywhere and run the commands below at Generating Keys.

### MacOS

TBD

### Generating Keys
For generating keys, run:

```bash
keys-generator btc <page number>
keys-generator eth <page number>
```

For searching by private key, run:
```bash
keys-generator btc-search <btc private key>
keys-generator eth-search <eth private key>
```

## License

This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
