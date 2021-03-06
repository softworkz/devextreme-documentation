Edit the `src\app\app-navigation.ts` file to configure navigation menu items. Each item configuration can have the following fields:

- **text** - the item's text

- **icon** - the item's [icon](/Documentation/Guide/Themes_and_Styles/Icons/)

- **path** - a navigation path associated with the item

- **items** - child items

[note] A menu item should either navigate to a page OR include subitems. For that reason, do not specify both **path** and **items** for the same menu item.

    <!-- tab: JavaScript -->
    {
        text: 'Category',
        icon: 'folder',
        items: [{
            text: 'About',
            path: '/about'
        }]
    }