# Wallapop screen assets for iOS & Android

This is a small **<a href="https://www.sketchapp.com/">Sketch</a>** project with the design of some screens and the iOS/Android assets for <a href="https://www.wallapop.com/">Wallapop</a>, an app to buy & sell things locally. It is made with Sketch v41.

Additionally, a **<a href="https://marvelapp.com">Marvel</a>** prototype has been made to test the UI functionality. It can be online executed at <a href="https://marvelapp.com/3013974">https://marvelapp.com/3013974</a>.

<img alt="screenshot" src="https://cloud.githubusercontent.com/assets/18370149/26029307/3500fc84-3832-11e7-8049-333db9a99c43.jpg">

&nbsp;
#### Contents of the repository:

- **readme.md**: the file with the present description.

- **wallapop.sketch**: Sketch file with the screen designs and the resources to generate the mobile device assets for iOS and Android.

- **/iOS_assets**: folder with the iOS assets generated by Sketch (sizes 1x, 2x and 3x).

- **/Android_assets**: folder with the Android assets generated by Sketch using the **<a href="https://app.zeplin.io/welcome.html">Zeplin plugin</a>** (sizes mdpi, hdpi, xhdpi, xxhdpi and xxxhdpi).

&nbsp;
#### Some considerations about the Marvel prototype:

- The **wallapop.sketch** file version in the repository is not exactly the same than the used to build the Marvel prototype, since it was necessary to extend the height of the original artwork in order to simulate the scroll functionality of the first screen (*Product search*). This is the only difference with the file in the repository.

- Since the scroll simulation in Marvel does not work very well, the proximity selector and the upload button are tied to the beggining and to the end of the product list, respectively. In the real app these elements would be floating over the scrolling list.

- For similar reasons, to simulate the scroll of the *Product detail* screen, the navigation and status bars are left opaque, while in the real app they should be semi-transparent.

- To simulate the effect of showing/hiding the drawer menu, "push right"/"push left" transitions have been used between the *Drawer menu* and the *Product search* screens. This does not match 100% the behavior of the real app, but works well to simulate these effects.

&nbsp;
#### List of generated assets for each screen:

- **Product search**:
    *  btn_common_filter
    *  btn_drawer_menu
    *  btn_floating_new
    *  chevron_down_black
    *  icon_search

&nbsp;
- **Drawer menu**:
    *  chevron_down_gray
    *  icon_menu_categories
    *  icon_menu_collections
    *  icon_menu_help
    *  icon_menu_invite
    *  icon_menu_magazine
    *  icon_menu_messages
    *  icon_menu_new
    *  icon_menu_notifications

&nbsp;
- **Product detail**:
    *  btn_facebook
    *  btn_gmail
    *  btn_messenger
    *  btn_nav_back
    *  btn_nav_favorite
    *  btn_nav_options
    *  btn_nav_share
    *  btn_twitter
    *  btn_whatsapp
    *  icon_default_avatar
    *  icon_emphasized_product
    *  icon_favorite_counter
    *  icon_location
    *  icon_star_0
    *  icon_star_50
    *  icon_star_100
    *  icon_view_counter

&nbsp;
- **New product**:
    *  btn_close
    *  chevron_right_gray (*)
    *  icon_camera (*)

    (*) The *chevron_right_gray* and *icon_camera* assets do not appear as independent elements in this screen, both have been exported from the page *Symbols*, since they are part of other symbols used in this screen.
