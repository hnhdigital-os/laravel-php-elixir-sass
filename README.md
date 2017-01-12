```
__________.__          ___________.__  .__       .__        
\______   \  |__ ______\_   _____/|  | |__|__  __|__|______ 
 |     ___/  |  \\____ \|    __)_ |  | |  \  \/  /  \_  __ \
 |    |   |   Y  \  |_> >        \|  |_|  |>    <|  ||  | \/
 |____|   |___|  /   __/_______  /|____/__/__/\_ \__||__|   
               \/|__|          \/               \/          
                                                 SASS Module
```

Provides the ability to generate revision hashes on files in a specified files or folder.


### SASS

Processes and compiles a *.scss file and outputs it to specified path.

Formatted as: {SOURCE_FILE_PATH}: {DESTINATION_FILE_PATH}

```yaml
sass:
    PATH_SASS + /app.scss: PATH_PUBLIC_ASSETS + /vendor/app.css
```
