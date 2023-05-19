# How to install the custom apps

## Eternal Jukebox

1. Run `spicetify config-dir` to open the spicetify folder
2. Go to the `CustomApps` folder
3. Create a `eternal-jukebox` folder
4. Copy the files from the [custom app's dist branch](https://github.com/Pithaya/spicetify-apps-dist/tree/dist/eternal-jukebox) inside it.

Then, run the following commands:

```sh
spicetify config custom_apps eternal-jukebox
spicetify apply
```

# How to uninstall the custom apps

## Eternal Jukebox

1. Run `spicetify config-dir` to open the spicetify folder
2. Go to the `CustomApps` folder
3. Delete the `eternal-jukebox` folder

Then, run the following commands:

```sh
spicetify config custom_apps eternal-jukebox-
spicetify apply
```
