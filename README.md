# Qualcomm Boot Firmware CI/CD repo

The Boot Firmware CI/CD repo is meant to host boot firmware blobs for Qualcomm platforms along with supporting the CI/CD framework for all the open
source boot firmware stack components like [Trusted Firmware-A](https://www.trustedfirmware.org/projects/tf-a/), [OP-TEE](https://www.trustedfirmware.org/projects/op-tee), [edk2](https://github.com/tianocore/tianocore.github.io/wiki/EDK-II) and [U-Boot](https://docs.u-boot-project.org/en/latest/index.html).

## Branches

**main**: Primary development branch. Contributors should develop submissions based on this branch, and submit pull requests to this branch.

## Usage

Boot Firmware artifacts published in this repo can be consumed by distros to bring-up Qualcomm platforms.

## Development

Development happens via regular github PRs.

## Getting in Contact

* [Report an Issue on GitHub](../../issues)

## License

[BSD-3-clause License](https://spdx.org/licenses/BSD-3-Clause.html). See [LICENSE.txt](LICENSE.txt) for the full license text.

For Qualcomm binary blobs, see corresponding license under [qc_blobs](qc_blobs).
