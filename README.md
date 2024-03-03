# SPINVAE-2: Synthesizer Preset Interpolation VAE (v2)

Work in progress.

Audio examples are available on the [companion website](https://gwendal-lv.github.io/spinvae2).

## Installation Notes

- Had to move data/regenerate.py to root directory
- Add utils/config_confidential.py (Made an example config in utils)
- Updating requirements.txt
- Made surgepy / renderman imports optional, trying dawdreamer

### Installing Dexed
```bash
wget https://github.com/asb2m10/dexed/releases/download/v0.9.6/dexed-0.9.6-lnx.zip
unzip dexed-0.9.6-lnx.zip
cp -R dexed-0.9.6-lnx/Dexed.vst3/ synth/
cp dexed-0.9.6-lnx/Dexed.vst3/Contents/x86_64-linux/Dexed.so synth/

# Clean up
rm -rf dexed-0.9.6-lnx
rm dexed-0.9.6-lnx.zip
```