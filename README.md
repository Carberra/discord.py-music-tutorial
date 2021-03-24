# Building a discord.py music bot (2020)

Welcome to the official GitHub repository for the [Building a discord.py music bot (2020)](https://www.youtube.com/playlist?list=PLYeOw6sTSy6ZIfraPiUsJWuxjqoL47U3u) series by [Carberra Tutorials](https://youtube.carberra.xyz)!

This repository is designed purely as a supplementary aid to the series, and should **NOT** be downloaded without having watched it first.

You can [browse the tags](https://github.com/Carberra/discord.py-music-tutorial/releases) to view the code as it was after a specific episode.

## Prerequisites

### Version table

|                       | Required | Used in series |
| --------------------- | -------- | -------------- |
| **Python**            | >= 3.5.0 | 3.9.2*         |
| **discord.py[voice]** | >= 1.5.0 | 1.6.0*         |
| **wavelink**          | >= 0.9.0 | 0.9.9*         |

*This is the latest of multiple versions used.

### Installing required libraries

To install the necessary libraries, run one of the the following commands:

```bash
# Windows
py -3.9 -m pip install discord.py[voice] wavelink

# Linux/macOS
python3.9 -m pip install discord.py[voice] wavelink

# In a virtual environment
pip install discord.py[voice] wavelink
```

You will also need:

- [OpenJDK 13.0.2](https://jdk.java.net/archive/) (make sure to download the right one for your OS)
- The latest version of [Lavalink](https://ci.fredboat.com/viewLog.html?buildId=lastSuccessful&buildTypeId=Lavalink_Build&tab=artifacts&guest=1) (in the videos I said 1071, but this version no longer works)
- An [application.yml](https://github.com/Frederikam/Lavalink/blob/master/LavalinkServer/application.yml.example) file, with the host set to 127.0.0.1

## License

This repository is made available via the [BSD 3-Clause License](https://github.com/Carberra/discord.py-music-tutorial/blob/master/LICENSE).

## Help and further information

If you need help using this repository, [watch the series](https://www.youtube.com/playlist?list=PLYeOw6sTSy6ZIfraPiUsJWuxjqoL47U3u). If you still need help beyond that, [join the Carberra Tutorials Discord server](https://discord.carberra.xyz).
