**Deeply appreciate [iGerman00](https://gist.github.com/iGerman00)'s effort.**  

# Usage  
- Use **safari**  
- [Download the JS file](https://raw.githubusercontent.com/brakingdown/5.1-support/refs/heads/main/cadmium-playercore-6.0050.784.911_ENABLE_5.1_.js) and save it on your Mac  

1. [Enable Safari's Developer Tools](https://support.apple.com/guide/safari/use-the-developer-tools-in-the-develop-menu-sfri20948/mac#:~:text=If%20you%20don%27t%20see,Show%20features%20for%20web%20developers.”)  
2. Navigate to Netflix, start playing some content, then pause it
3. Press `Command+Option+I`
4. Go into the **Network** tab
5. In the little search bar, type **cadmium-playercore**, it should show you one request
6. Right-click the request, select **Create Response Local Override**. You will be taken to the Sources tab
7. In the top right, click **Map to File** and select the modified cadmium that you downloaded earlier
8. Reload the page
# Features​  
- Enabled **5.1 audio** support
- Enabled audio track visibility in the player to have the ability of toggling between 5.1 and 2.0 easily

# Development​  
The modifications are marked with `//DOLBY-MOD` comments. There are very few modifications, so if the version is updated, you can refer to the old version and make the changes yourself.

# Acknowledgments  
https://forums.macrumors.com/threads/netflix-on-safari-with-dolby-atmos.2329766/page-2  
https://gist.github.com/iGerman00/df6c3b6d56c1df30fb85658a0a96999c
