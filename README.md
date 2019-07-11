# Yule-RStudio
Yule-RStudio
This theme is from: https://www.garrickadenbuie.com/blog/yule-rstudio-theme/


Installation

You’ll need RStudio version 1.2. Grab the preview version here.

    Run the following code in RStudio to download and apply the theme.

    yule_theme <- fs::path_temp("Yule-RStudio", ext = "rstheme")
    download.file("https://git.io/yule-rstudio", yule_theme)
    rstudioapi::addTheme(yule_theme, apply = TRUE)

Manual Installation

If the steps above don’t work, you can manually download the Yule-RStudio.rstheme file and place it in .R/rstudio/themes in your R home directory (see path.expand("~")). Then, in the RStudio appearance settings, select the Yule RStudio editor theme.


    lab_theme <- fs::path_temp("JhuangLab", ext = "rstheme")
    download.file("https://github.com/jinyancool/Yule-RStudio/edit/master/Jhuanglab.rstheme", lab_theme)
    rstudioapi::addTheme(lab_theme, apply = TRUE)
