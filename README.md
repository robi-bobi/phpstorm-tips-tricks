# phpstorm-tips-tricks
Various PHPStorm Tips, Tricks &amp; HOWTOs

##.gitignore
###.idea
Add `.idea` to your `.gitignore` file.

##Tell PHPStorm about var types in your template files
When you inherit variables from other files, you can instruct PHPStorm which type or class they belong to at the beginning of the file, ex:
`@var WP_Query $contractors`
As long as the class is indexed, PHPStorm will now provide autocompletion and validation
![alt tag](https://robi-bobi.github.io/phpstorm-tips-tricks/import_var_with_types.png)
