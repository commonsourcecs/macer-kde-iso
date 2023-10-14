# MaCeR KDE Editions
[![iso_build](https://github.com/commonsourcecs/macer-kde-iso/workflows/iso_build/badge.svg)](https://github.com/commonsourcecs/macer-kde-iso/actions)

## description

KDE Plasma ISO for MaCeR (Manjaro Linux cscs edition - Recovery). 

These are automated builds currently for testing. 

## where can I download an iso?

Images are built and uploaded in a relatively regular interval to [github releases](https://github.com/commonsourcecs/macer-kde-iso/releases).

## sources

- [iso profile](https://github.com/commonsourcecs/iso-profiles/tree/master/community/macer-kde)
- [desktop settings](https://gitlab.manjaro.org/profiles-and-settings/manjaro-kde-settings)

## building

1. check out the iso profile
2. `buildiso -p macer-kde`

## credentials

```
user: macer
password: macer
```
## Extracting

ISOs are provided in multipart zip files because of the filesize restriction of github.</br>
To extract the iso download all the zipped parts and open the zip file with file-roller, engrampa or 7z.</br>
This should automatically extract the iso from all the files.</br>
Of course you can also use the terminal. 
```
cat manjaro-macer-kde.iso.z* > macer-kde.iso.zip
unzip macer-kde.iso.zip
```
