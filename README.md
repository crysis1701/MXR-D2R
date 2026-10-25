# MXR: install and play together

MXR is a Diablo II: Resurrected mod with faster power growth, harder and denser monsters, deeper skill synergies, and the Geomancy tree for the Sorceress. It runs on **D2RLAN** (D2R version 2.4) and is played solo or with friends in TCP/IP games.

MXR is an original mod. It is inspired by the feel of Median XL but uses none of Median XL's files or content.

## What you need

- Diablo II: Resurrected, legally owned
- D2RLAN, set up following its own guide
- About 10 MB for MXR itself

## Install

1. Install D2RLAN, including the .NET runtime in its `_InstallMeFirst` folder.
2. Add MXR in one of two ways:
   - **Launcher:** use the MXR download link in D2RLAN, if your launcher lists it.
   - **Manual:** unzip `MXR-<version>.zip` into `D2RLAN\D2R\Mods`. You should end up with `D2RLAN\D2R\Mods\MXR\MXR.mpq` and `D2RLAN\D2R\Mods\MXR\version.txt`.
3. Start D2RLAN, choose **MXR** as the mod, and launch.

MXR uses its own save folder (`MXR`), so its characters stay apart from vanilla and other mods.

## Play together

MXR games are hosted by a player over TCP/IP. There is no always-on server: a game lasts while its host is in it.

1. **Same version for everyone.** Compare `Mods\MXR\version.txt` before playing. Different versions will not work together.
2. **Join one network with Radmin VPN** (free, https://radmin-vpn.com). Choose *Join Network*, then the *Gaming Network* tab, search for "Diablo", and join **Diablo II: Resurrected**.
3. **Host:** allow D2R through Windows Firewall. Open *Windows Defender Firewall*, then *Allow an app through firewall*, then *Change settings*, and tick `d2r.exe` and Diablo II: Resurrected. Create a TCP/IP game in MXR.
4. **Others:** join the host's game using the host's Radmin VPN IP address.
5. **Optional:** run **Beacon**, which comes with D2RLAN, to list hosted games and join with one click.

These steps follow D2RLAN's own `HOW_TO_PLAY_WITH_OTHERS.txt`.

## Updating

When a new MXR version is released, D2RLAN can offer the update from the launcher. Otherwise, replace the `Mods\MXR` folder with the new zip's contents. Characters are kept, but everyone in a game must update together.
