# iztiev's scoop bucket

A [Scoop](https://scoop.sh/) bucket for apps that I could not find in other buckets

## Usage

After installing [Scoop](https://scoop.sh/), enter the following line in a
Command Prompt or PowerShell window:

```powershell
scoop bucket add iztiev https://github.com/iztiev/scoop.git
```

Once this is done, you can install any app from this bucket (check the list
of files in the
[`bucket/` directory](https://github.com/iztiev/scoop/tree/main/bucket)).
For instance, use the following command:

```powershell
# Don't include the .json file extension in the app name
scoop install iztiev/ttfautohint
```

## Updating applications in this bucket

For manifests that contain an `autoupdate` section, there's a GitHub Actions
workflow that runs every day and commits updated manifests to the repository.
No need to open a pull request to update those manifests.

For manifests that don't contain an `autoupdate` section, feel free to open a
pull request to update them to the latest version. You can also
[add an `autoupdate` section to the manifest](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifest-Autoupdate)
to ensure the application always remains up-to-date in the future.

## License

Files in this repository are licensed under MIT License,
see [LICENSE.md](LICENSE.md) for more information.