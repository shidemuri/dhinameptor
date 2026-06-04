# Dhinameptor
This is a decompilation of [DHINAMEPTOR 1.00 by ニシキガツオ](https://kohada.ushimairi.com/game_dhina.html)

This doesn't aim to be a perfect reconstruction (as there aren't any HSP decompilation toolchains that I'm aware of besides the HSP Decompiler), but at least the codebase is readable and behavior matches the original game.

## Usage
Place all game files on the same folder as this repo, then build and run `start.hsp` with any version of Hot Soup Processor. (hsp351 and hsp36 are known to work, but realistically any hsp version dating back to at least 2014 should do)

(as the original game download is down, an archived version will be present here soon)

### Libraries

HSP DirectSound Extension ver.2.20 [(readme)](http://taillove.jp/mia/plugin/arc/dsoundex.txt) [(library download)](http://taillove.jp/mia/plugin/arc/dsoundex.lzh) (checksum matches with the game's own copy of `dsoundex.hpi`)

### Credits
Original game belongs to the ニシキガツオ team.

Code was extracted with [HSP-Decompiler](https://github.com/YSRKEN/HSP-Decompiler)