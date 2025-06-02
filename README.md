This is for hack and rework for xiaomi sound gpt

# hack

the `parse_gpt.py` is used to extract the info like UUID and partition name from the gpt binary of the dump image.
The gpt binary is the LBA0-LBA33, the LBA is usually 512 or 4K bytes. The script can detect the sector size.
