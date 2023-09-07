1. cd ./../
2. hugo new site "name-of-repo"
3. From your project's root directory, initiate the hugo module system if you
   haven't already:

```
$ hugo mod init github.com/<your_user>/<your_project>
```

4. Add the theme's repo to your config.toml:

```toml
  theme = ["github.com/cromozooom/calina"]
```
