
#D8 port upgrade notes

- Fontawesome and jquery_update do not have D8 port so added font awesome from cdn and used default jquery version from drupal.
- Some blocks missing D8 like secondary and primary menu.
- Due to missing blocks so some front end restructure needed.
- Bootstrap D8 port have some enhancements and rely on html5 elements.
- Theme settings and preprocessing rewritten so test your configuration.
- Totally removed all markup from drumob.theme to .twig files.
- Add block--system-branding-block.html.twig and region--content.html.twig plus html.html.twig and page.tpl.twig See templates folder.


# DruMob ( Drupal theme)

### Introduction
DruMob is a Drupal based theme. It is highly customizable and allows anyone to
insert mobile optimised toolbars, side menu and mobile header into any 
Drupal instance.

### Demo
http://www.masarsoft.com/demo/drumob - It's recommended to open this link in 
your mobile internet browser.

### Requirements
This theme requires the following:
- Bootstrap theme.
- Jquery Update module.
- Font Awesome module.

### Installation
Install as you would normally install a Drupal theme, be sure Bootstrap theme
is installed first. for further information here is more help:
Youtube (https://youtu.be/1GYToBztYg0).

### Configuration
* Set tabs labels,icons and links:Appearance->Theme Settings->Toolbar Settings.
* Set page loading icon:Appearance->Theme Settings->Loading Animation Settings.
* For icons you can use font awesome library http://fontawesome.io/icons

### Troubleshooting
If icons not displayed be sure FontAwesome module is installed and its library
is located in libraries folder.

### Maintainers
Current maintainers:
* Essam Al-Qaie (3ssom) - https://www.drupal.org/u/3ssom
* Nahedh Alharbi (nahedh) - https://www.drupal.org/u/nahedh
* Stefan Tachev (stefan_tachev) - https://www.drupal.org/u/stefan_tachev
