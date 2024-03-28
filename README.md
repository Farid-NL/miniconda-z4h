# miniconda-z4h

<p align="center">
Manage miniconda installation as a external z4h plugin
</p>

## Usage

- Add the following lines in your `.zshrc`.
  ```shell
  # Above `z4h init || return`
  zstyle :z4h:Farid-NL/miniconda-z4h postinstall '$Z4H_PACKAGE_DIR install-miniconda-z4h'
  z4h install Farid-NL/miniconda-z4h

  # Take this line as a reference, DO NOT add it
  z4h init || return

  # Below `z4h init || return`
  z4h load Farid-NL/miniconda-z4h
  ```

## Caveats
 It relies on unspecified internal details of z4h that can change without any notice.
