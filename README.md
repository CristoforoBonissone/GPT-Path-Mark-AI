# GPT Path Mark AI

GPT Path Mark AI is a lightweight storage benchmark for Windows.

Unlike traditional low-level synthetic disk benchmarks, GPT Path Mark AI
measures the performance of a selected folder through the Windows file system.

This provides results that closely represent common operations such as:

- Copying large files
- Backup operations
- Disk imaging
- ISO creation
- Video file transfers
- SSD and NVMe performance testing

## Current benchmark

### SEQ1M Q8T1

- Sequential read and write
- 1 MiB block size
- Queue depth 8
- 1 software thread

The test is designed to measure sustained storage throughput.

## System requirements

- Microsoft Windows
- SSD, NVMe, HDD or other file-system-accessible storage device

## Download

Download the latest version from the Releases section of this repository.

## Author

Cristoforo Bonissone  
https://www.dacris.it/gptpm/index.html

## License

MIT License
