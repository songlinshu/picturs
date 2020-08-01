<div align="center">
  <img src="https://raw.githubusercontent.com/estebanborai/iconize/master/assets/test.png" height="150" width="150" />
  <h1>iconize</h1>
  <small>CLI utility for building multiplatform icons</small>
</div>

**iconize** is a CLI utility that resizes and encode image files for multiple platforms, such
as MacOS, Linux and Windows.

## Usage

`iconize [OPTIONS] <input_file> --target <target>`

The only argument required is the `input_file` which should be a valid image file. Specs
about the [File Requirements]().

### Options

Short | Long | Usage | Description
-- | -- | -- | --
`-o` | `--output` | `iconize -o icons/` | The path to the output directory for your icons
`-t` | `--target` | `iconize -t osx, windows` | The target OS for icon files

## File Requirements

Depending on the `target` OS, your `input file` must match different sizes for
**iconize** to process such file.

Target OS | Target | Minimum Expected Dimensions | Format
--- | --- | --- | ---
macOS | `osx` | 512x512 | `PNG`
Linux | `linux` | 16x16 | `PNG`
Windows | `windows` | 256x256 | `PNG`


## Contributing

Contributions to this repository are welcome, feel free to open either an Issue or
Pull Request.

## License

Licensed under the MIT License
