## ANNOUNCEMENTS ##

THIS EXTENSION IS DEPRECATED!

Active development continues at Minimalist for Everything:

https://chrome.google.com/webstore/detail/bmihblnpomgpjkfddepdpdafhhepdbek

Please disable Minimalist for Gmail if you have it installed and install Minimalist for Everything instead.


## WHAT DOES IT DO? ##

> It is a personalized solution for those who are tired of useless and distracting elements in the Gmail interface.
> It removes as much or as little as you want. It also adds functionality if you so choose.
> Look around the options page to see what it does first hand. Link below.


## PERMISSIONS ##

> Learn more about Chrome Extension permissions here: http://www.google.com/support/chrome/bin/answer.py?hl=en&answer=186213
> If you look as the permissions required by similar extensions in the Web Store, you will see that they are exactly the same
> so before you make assumptions based on two short and broad statements, please read the following:

> == "tabs"
    * This permissions results in the "This extensions can access your browsing history" warning.
    * I **NEVER** access your browsing history.
    * I need this permission to open tabs. I use this to open the options page on major updates.
    * This permission is also used to refresh the Gmail tab when you save your settings.
> == "bookmarks"
    * This permission results in the "This item can access your bookmars" warning.
    * I **NEVER** access, read, modify, store, or transmit any of bookmarks.
    * I need this permission to create a bookmark that is used to sync settings accross computers.
> == "http://*/*", "https://*/*"
    * This permission results in the "This extension can access your data on all websites" warning.
    * I **NEVER** access, read, store, or transmit your personal data.
    * I need this permission to run user scripts behind specific pages in the browser.
    * These scripts inject Javascript and CSS into Gmail to enhance functionality and hide elements
    * The reason I ask for permissions to all pages and not just Gmail is because of my open in Gmail feature
> > > which replaces all "mailto:" links in websites with a script that opens clickable email addresses in Gmail.


> Still don't trust me? Go to https://github.com/anstosa/Minimalist-Gmail to see the entire source code.


## OPTIONS ##

> The Options page is easy to use and interactive features:
  * Screenshots when you mouseover options so you know what you're changing
  * Organized tabbed navigation
  * See it in action here: http://www.anselsantosa.com/sites/MinimalistGmail/options.html

> The following elements can be modified individually:
> == GENERAL
    * Hide Minimalist for Gmail options icon
    * Custom loading screen
    * Customize button colors
    * Rounded corners on input fields and textareas
    * Hide inactive scrollbar
    * Show transition animations
    * Custom CSS input
> == NOTIFICATIONS
    * Favicon unread count
    * Desktop notifications
> == GOOGLE BAR
    * Hide Google bar [to toggle when hidden](click.md)
    * Hide background & border
    * Hide Google links
    * Replace Google links with custom menu
    * Hide logged in
    * Hide Labs icon
    * Hide Settings link
    * Hide Help link
    * Hide Sign out link
> == HEADER
    * Hide header [to toggle when hidden](click.md)
    * Hide logo
    * Use custom logo
    * Hide all search
    * Hide mail search button
    * Hide web search button
    * Hide search sub-links
> == MAIN
    * Hide row borders
    * Hide grabbers in rows
    * Simplify rows until mouseover
    * Show starred item row highlighting
    * Show unread item highlighting
    * Show select/hover highlights [mail and contacts. keyboard navigation support](in.md)
    * Hide zero-inbox whitespace
    * Hide star icons
    * Show better attachment icons [specific, two built in styles and custom input via URL or base64](file.md)
    * Floating toolbars scroll with page
    * Hide top toolbar
    * Hide bottom toolbar
    * Use classic selection links instead of dropdown menu
    * Hide checkbox tools in toolbar
    * Hide Archive, Spam, Delete buttons
    * Hide Move to, Labels buttons
    * Hide More actions button
    * Hide Refresh link
    * Hide reply textbox in message view
    * Hide "No new mail! Want to read updates from your favorite sites? Try Google Reader"
    * Hide People Widget
    * Hide sidebar ads
    * Hide experimental bottom ads
> == NAVIGATION
    * Hide navigation
    * Floating nav bar scrolls with page
    * Custom nav width
    * Hide dividing lines
    * Hide top of nav
    * Hide mail button
    * Hide contacts button
    * Hide tasks button
    * Hide middle of nav
    * Hide compose mail button
    * Hide Spam count
    * Hide Buzz count
    * Hide icons
    * Hide more count
    * Hide more link
    * Hide invites
> == CHAT
    * Hide chat
    * Hide "Search, add, or invite" box in chat
    * Hide "Set status here"
    * Hide "Sign in to AIM"
    * Hide "You are invisible" alert in chat
    * Hide offline chat contacts
    * Hide offline sms contacts
    * Hide idle chat contacts
    * Hide chat statuses
> == FOOTER
    * Tips
    * Options
    * Legal
    * Storage [classic](classic.md)
    * Storage > Label
    * Storage > Graphic
    * Storage > Verbose
    * Storage > Menu
    * Account activity [or move to top](remove.md)
> == MORE?
    * Leave feature suggestions in the Issue Tracker: http://code.google.com/p/minimalist-gmail/issues


## HOW DO I WORK IT? ##

> All the instructions you need are on the support page:
> http://code.google.com/p/minimalist-gmail/wiki/Support


## ISSUES TRACKING ##

> I test as thoroughly as I can before each release, but bugs are bound to get through.
> Read, track, and submit bugs in the Issue Tracker:
> http://code.google.com/p/minimalist-gmail/issues


## QUESTION? ##

  * Ping me on Twitter: @anstosa
  * Email me: ansel@anselsantosa.com


## COMING SOON ##

> Want to recommend a feature? Submit it in the Issues Tracker:
> http://code.google.com/p/minimalist-gmail/issues/list


## CHANGELOG ##

> == 1.7.38 [JUN](XX.md)
    * Fixed: Hide Chat > Search now working after People Widget rollout
> == 1.7.37 [JUN](29.md)
    * Added: Hide People Widget
    * Changed: Hide Sidebar Ads no longer collapses sidebar
    * Fixed: Hide Sidebar Ads breaking layout after People Widget rollout
> == 1.7.36 [JUN](10.md)
    * Fixed: Header not hiding
> == 1.7.35 [JUN](9.md)
    * Fixed: Messages opening below inbox when toolbar is floating
> == 1.7.34 [JUN](7.md)
    * Changed: Verbaige for the priority button workaround
    * Fixed: Hide logo not working
    * Fixed: Custom Logo not working
    * Fixed: Hide header not always working
    * Fixed: Hide chat hiding next gadget in list
    * Fixed: Floating toolbars breaking layout when activated
> == 1.7.33 [MAY](24.md)
    * Fixed: Hide sidebar ads hiding sidebar but not ads
> == 1.7.32 [MAY](20.md)
    * Fixed: Custom buttons not working in late Gmail Priority update
> == 1.7.31 [MAY](20.md)
    * Fixed: Star icon not hiding in navigation
    * Fixed: Favicon notifications not showing
    * Fixed: Hide xero-inbox whitespace hiding chat
> == 1.7.30 [MAY](18.md)
    * Fixed: Unreliability in 13.**> == 1.7.29 [MAY](17.md)
    * Fixed: Typo in background.html
> == 1.7.28 [MAY](17.md)
    * Fixed: Hide Chat not working on secondary accounts.
    * Fixed: Workaround for Chromium 82784: http://goo.gl/XZMSr. No icon for affected builds
> == 1.7.27 [MAY](11.md)
    * Fixed: Floating toolbars not working on some pages
> == 1.7.26 [MAY](10.md)
    * Fixed: Hide Chat hiding all gadgets
> == 1.7.25 [MAY](9.md)
    * Fixed: Zero inbox whitespace hiding chat
    * Fixed: Chat not hiding (for real this time)
> == 1.7.24 [MAY](8.md)
    * Fixed: Zero inbox whitespace not hiding
    * Fixed: Chat not hiding
> == 1.7.23 [APR](6.md)
    * Fixed: Classic storage footer always hidden in non-apps mail
> == 1.7.22 [APR](4.md)
    * Fixed: Classic storage footer no longer hiding in non-apps mail
> == 1.7.21 [APR](2.md)
    * Fixed: Check for Google Apps did not detect all Google Apps accounts.
> == 1.7.20 [APR](2.md)
    * Fixed: 1.7.19 broke footer options in Google Apps
    * Fixed: Toolbar button hiding in Google Apps
> == 1.7.19 [APR](1.md)
    * Fixed: Some footer options not working
    * Fixed: Hide/Custom logo interfering with Compose Mail view
> == 1.7.18 [MAR](27.md)
    * Fixed: Compose pop-out appears with tiled custom logos when not opened from within Gmail
    * Fixed: New refresh button not hiding
> == 1.7.17 [MAR](25.md)
    * Fixed: Some CSS-based chat and navigation features broken 3/25
> == 1.7.16 [MAR](25.md)
    * Fixed: favicon counter only updating once per load
> == 1.7.15 [MAR](24.md)
    * Fixed: Send with Gmail and similar extensions popup compose dialog with missing fields
> == 1.7.14 [MAR](20.md)
    * Changed: URL bar icons are smaller and lighter to not be intrusive
> == 1.7.13 [MAR](18.md)
    * Changed: Logos to comply with Google's branding guidelines
    * Fixed: Width bug in stable and beta channels with Hide Sidebar ads enabled [Stephen!](thanks.md)
> == 1.7.12 [MAR](16.md)
    * Fixed: Make Google Bar invisible until mouseover not appearing on hover [real this time](for.md)
    * Fixed: Some chat features not working after
> == 1.7.11 [MAR](13.md)
    * Fixed: Make Google Bar invisible until mouseover not appearing on hover
> == 1.7.10 [MAR](13.md)
    * Imporoved: resource usage for apps check and floating element init functions
    * Fixed: Floating nav and Toolbar not working
> == 1.7.9 [MAR](12.md)
    * Fixed: Hide nav not working in Google Apps accounts
    * Fixed: Hide Header and Google Bar not working together in Google Apps accounts with new Google Bar
> == 1.7.8 [MAR](11.md)
    * Fixed: Contextual information showing over messages with hide sidebar ads
> == 1.7.7 [MAR](11.md)
    * Fixed: Sidebar ads not hiding
> == 1.7.6 [MAR](11.md)
    * Fixed: Sidebar info overlapping messages with ads hidden [entirely for now](hidden.md)
    * Fixed: Floating nav not clickable
> == 1.7.5 [MAR](10.md)
    * Fixed: Hide header and Hide Google Bar problems with old Google bar
    * Fixed: Floating nav floating over messages in small windows
    * Fixed: Hide Nav and Floating Nav conflicting
    * Improved: Larger margin at bottom of General tab to facilitate Custom CSS resizing
> == 1.7.4 [MAR](8.md)
    * Fixed: Google bar and header hiding eachother
    * Fixed: Checkbox list displaying vertically in stable and beta channels
> == 1.7.3 [MAR](6.md)
    * Added: Experimental sync feature
    * Fixed: Navigation hotkey not working after 1.7.1
> == 1.7.2 [MAR](3.md)
    * Fixed: Row highlighting disabled after 1.7.1
    * Fixed: Header not hiding after 1.7.1 Gmail update
> == 1.7.1 [MAR](3.md)
    * Added: Minimalist for Google Reader info
    * Improved: all favicons updated to Google's most recent versions
    * Improved: favicon unread icon numbers now black on grey instead of gray on yellow
    * Improved: Google Bar, Header, and Navigation toggling code
    * Fixed: Dividing bars not hidden in Google User Bar for Google Apps users
    * Fixed: Priority Inbox menu's broken with checkbox tools list
    * Fixed: Show checkbox list not showing up inline
    * Fixed: Message and list properties not animating
    * Fixed: Floating toolbar gets stuck at top of inbox
> == 1.7.0 [Feb](26.md)
    * Added: Floating navigation scrolls with page
    * Added: Floating toolbars scroll with page
> == 1.6.23 [Feb](24.md)
    * Fixed: Make invisible until mouseover not reappearing on mouseover in Google Apps
    * Fixed: Make invisible until mouseover not hiding Google Apps links
> == 1.6.22 [Feb](22.md)
    * Improved: Simplify rows code, also attachment icons fade until selction or mouseover
> == 1.6.21 [Feb](22.md)
    * Fixed: Checked checkboxes don't stay visible with Simplify Rows
> == 1.6.20 [Feb](20.md)
    * Fixed: Problems with old Google Bar
> == 1.6.19 [Feb](16.md)
    * Fixed: "More" drop-down on new Google bar not hide-able
> == 1.6.18 [Feb](16.md)
    * Added: Donate tab in options
    * Fixed: Selection indicator hidden in simplify rows
    * Fixed: Install failure on Chrome for Fedora
    * Fixed: Google Bar features incompatible with new Google Bar
    * Fixed: Activity under new Google Bar when moved to top
> == 1.6.17 [Feb](10.md)
    * Fixed: Offline chat contacts not hiding in French Gmail
> == 1.6.16 [Feb](10.md)
    * Removed: Calendar script from easter egg
    * Fixed: Custom checkbox tools button shifting to left on hover
> == 1.6.15 [Feb](10.md)
    * Fixed: Custom buttons shifting way left on hover
> == 1.6.14 [Feb](9.md)
    * Fixed: stupid typo...
> == 1.6.13 [Feb](9.md)
    * Improved: Simplify rows dims labels until mouseover
    * Fixed: Simplify rows permanently hiding checkboxes
    * Fixed: Offline and idle chat contacts not hiding in French Gmail
    * Fixed: [g ](.md) + [l ](.md) hiding header when it was open
    * Fixed: Custom buttons shifting to left on hover
> == 1.6.12 [Feb](7.md)
    * Fixed: Naming convension not adhereing to Google's branding policies
    * Fixed: [g ](.md) + [l ](.md) unhiding Google Bar when Header wasn't hidden
> == 1.6.11 [Feb](4.md)
    * Fixed: Keyboard shortcuts only working if Select/hover row highlights enabled
> == 1.6.10 [Feb](3.md)
    * Fixed: Options button in popup didn't open version notes on minor updates
> == 1.6.9 [Feb](3.md)
    * Added: Hide sms contacts in chat
    * Added: Hide Idle contacts in chat
    * Added: Hide "Sign in to AIM" in chat
    * Added: Hide Zero-inbox whitespace
    * Added: Hide dividing lines in navigation
    * Added: Hide grabbers in rows
    * Fixed: Search options in header not working on macs
    * Fixed: When select highlights are enabled and unread highlights aren't unread rows aren't highlighted on mouseover
> == 1.6.8 [Feb](2.md)
    * Fixed: Header not toggling when Hide Google Bar is enabled
    * Fixed: Header options not working
    * Fixed: Row highlights only working as expected with all enabled
> == 1.6.7 [Feb](1.md)
    * Fixed: Something stupid...
> == 1.6.6 [Feb](1.md)
    * Added: Color blending for row highlighting. [unread color + blue hover color = purple hover on unread item](red.md)
    * Fixed: Offline chat not hiding
    * Improved: Row selected with keyboard navigation with un-simplify
    * Improved: Total revamp of triggers and timers. Significant performance improvement. Especially while idle.
    * Changed: Move activity to top. Translucent and centered. Will not hide or fade with Google Bar or header.
    * Removed: Unread color for select/hover. Now when multiple cases overlap, the colors blend.
    * Removed: Hide Inbox link [to do universaly unless it's first on the list. Do it in Custom CSS](impossible.md)
> == 1.6.5
    * Fixed: Random backend stuff to make remote bug diagnostics easier
> == 1.6.4
    * Added: Made animated transitions optional [decrease performance on slower machines](may.md)
> == 1.6.3
    * Added: Very subtle transition effects
    * Added: Hide inactive scrollbar option
    * Added: mailto script is not optional for those with bugs on other sites or who use desktop clients
    * Added: Show "more" menu with custom Google Bar links with all original links included in the dropdown
    * Added: Made show nav on mouseover optional
    * Improved: First line no longer highlights as if selected for users who don't use keyboard navigation
    * Improved: [` ](.md) tilde key now toggles nav bar if hidden
    * Improved: [\ ](.md) now toggles header and gbar on and off [when either is hidden by default](only.md)
    * Improved: Performace improvement for keyboard navigation in messaged
    * Improved: Performace improvement for offline contact hiding
    * Fixed: Keyboard navigation past either end of list unhighlights top or bottom item
    * Fixed: Keyboard navigation not highlighting the right rows, not unhighlighting non-selected rows
    * Fixed: Displaying checkbox tools as list breaks all toolbar dropdowns
    * Fixed: Icon row from hidden sidebar floats over long subject lines
    * Fixed: [g ](.md) + [l ](.md) shortcut broken
    * Fixed: CPU obliteration bug. [Sorry, didn't notice it on my Quad Core i7 but turned my CR-48 into a rock :-)]
> == 1.6.2
    * Fixed: Messaged appearing below for unknown reasons [nav and custom nav width still broken for those users](hide.md)
> == 1.6.1
    * Fixed: Messages appearing below chat because of gadgets
> == 1.6.0
    * Added: Toggle Minimalist for Gmail on/off. New dropdown from URL bar icon allows toggling and link to Options
    * Added: "Panic!" button in URL icon dropdown. Just reloads the page but that fixes a lot of problems
    * Added: Reset option for custom button colors
    * Added: Hide "You are invisible" alert in chat
    * Added: "Settings saved" message for peace of mind and to remind you to refresh!
    * Added: Notes and explanations everywhere for clarification
    * Added: Custom navigation width
    * Added: Custom loading screen
    * Added: Rounded corners on fields and text areas
    * Added: Hide logo
    * Added: Hide Google Bar border & background
    * Added: Hide reply textbox in message. [r ](.md) and reply links still trigger reply pane
    * Added: Hide row borders
    * Added: Unread item highlighting
    * Added: Simplify rows, hides most elements in row until mouseover
    * Added: Hide Inbox link
    * Added: Hide "more" count
    * Added: Use classic selection link list instead of dropdown menu
    * Added: Custom CSS input for advanced users
    * Added: Import/Export settings and several presets
    * Improved: [/ ](.md) shortcut focuses search and unhides header if hidden. Rehide with [\ ](.md)
    * Improved: Toggle stripes are only tinted on mouseover. Ultra minimalists rejoice!
    * Improved: Activity no longer replaces Google Links when moved to top
    * Imporved: Google Bar toggle stripe now above Google Bar
    * Improved: If Google Bar and Header are both hidden, they share a toggle stripe
    * Improved: Resource usage. Should be a bit less bulky now
    * Improved: Options page scrolling and expandable element behavior
    * Improved: Added 6th custom link for Google Link Bar. "More" hides automatically
    * Improved: Added seperate hover/select row highlight color for unread items
    * Improved: Navigation now has click to toggle and show on mouseover
    * Fixed: Options page mouseovers should no longer appear outside the viewport on smaller screens
    * Fixed: Hide mail search doesn't work with apps search lab enabled
    * Fixed: Activity still visible if Google Bar hidden
    * Fixed: Easter Egg! Click "more" in title of the "More" tab to load my personal Voice, Reader, & Calendar Scripts
    * Fixed: Navigation not hiding
    * Fixed: No row highlight colors applied to first item on load [takes precendent](starred.md)
    * Fixed: Starred item highlight color not applied when superstars enabled
    * Fixed: OpenOffice formats not recognized by Better Attachment Icons
    * Fixed: Whitespace when hiding sidebar & package tracking infomation hidden
    * Fixed: Hide Chat hiding all gadgets. Will work with Drag & Drop but Chat must be second, after Compose, inbox etc.
    * Fixed: All Google User Bar elements causing problems
    * Fixed: Hide Offline not hiding offline cell phones
    * Fixed: Hide chat search box hiding RTM add task box
    * Fixed: Bottom toolbar not hiding in messages
> == 1.5.0
    * Added: Hide Google User bar elements [in, Labs icon, Settings, Help, Sign Out](logged.md) [[idea Sarah](good.md)]
    * Added: Hide Google Bar [to toggle stripe](click.md)
    * Added: Custom better attachment icons via URL or base64 input
    * Added: Vertical scrollbar is not invisible if page fits within window [disabled it instead of hiding it](Gmail.md)
    * Added: Hide "No new mail! Want to read updates from your favorite sites? Try Google Reader" [idea Sarah](good.md)
    * Improved: Hide header, new click to toggle stripe
    * Improved: Fallback fonts appear on options page until custom fonts are loaded from Google [low/no internet](for.md)
    * Improved: All options auto-save, no need to click save anymore [if that was confusing in the 1.4.0 update](sorry.md)
    * Fixed: Some screenshots not visible on new options page
> == 1.4.2
    * Fixed: Starred item highlighting broken again [seriously? Gmail changed class names twice this week...]
    * Fixed: Navigation not hiding
    * Fixed: Middle navigation not hiding
> == 1.4.1
    * Fixed: Legal option in Footer tab didn't save when checked
> == 1.4.0
    * Added: Custom Google bar. Swap out Google's choices with your 5 favorite links
    * Added: New better attachment icon options [CarlosJ](thanks.md)
    * Improved: Options page
    * Fixed: Google user info section hiding instead of navigation
> == 1.3.9
    * Added: Get the Reader link back in the Google Bar!
> == 1.3.8
    * Fixed: gbar not hiding
> == 1.3.7
    * Fixed: Inability to disable custom buttons
> == 1.3.6
    * Fixed: Manifest error
> == 1.3.5
    * Added: Custom button colors [idea jack limit](Great.md)
> == 1.3.4
    * Fixed: Desktop notifications active on mac without enabling option
> == 1.3.3
    * Fixed: Desktop notifications repeat all after browser reload
> == 1.3.2
    * Fixed: Desktop notifications not showing up on mac
> == 1.3.1
    * Improved: Clickable desktop notifications
    * Fixed: Desktop notifications
> == 1.3.0
    * Added: Hide Spam count
    * Added: Hide Buzz count
    * Added: Show unread count in favicon [to Peter Wooley for allowing me to republish his script](thanks.md)
    * Added: Desktop notifications [options coming next week](more.md)
    * Added: Better attachment icons
    * Improved: Gmail reloads on save automatically
    * Improved: Code optimization
    * Fixed: Header not hiding in some cases [fallback css](added.md)
> == 1.2.8
    * Toggle header when hidden by clicking blank area below gbar [idea ds](good.md)
    * Fixed: Web search not hiding
> == 1.2.7
    * Added: Easter egg [a minimalist Google Voice, Reader, and Calendar? Click the question mark](want.md)
    * Fixed: Bottom toolbar not hiding
> == 1.2.6
    * Fixed: Chat options hiding pop-up bars
> == 1.2.5
    * Fixed: Custom logo not displaying
> == 1.2.4
    * Improved: Default custom colors
> == 1.2.3
    * Added: donate link [please? :-)]
    * Added: Hide experimental bottom ads
    * Added: Hide classic storage in footer [apps, some themes](Google.md)
    * Improved: Google Apps support [in progress, please report bus](work.md)
    * Fixed: Color picker not showing default colors
> == 1.2.2
    * Added: visual color picker [for the idea EBreHNN](thanks.md)
> == 1.2.1
    * Added: Hide sidebar ads [contextual options and relocates above message](iconizes.md)
    * Added: Starred item row highlighting
    * Added: Hide Archive, Spam, Delete buttons
    * Added: Hide Move to, Labels buttons
    * Added: Hide More actions button
    * Added: Hide Refresh link
    * Added: Hide top toolbar
    * Fixed: Search button options not hiding the right elements
> == 1.2.0
    * Added: Hide navigation
    * Added: Hide middle nav section
    * Added: Hide Compose Mail button
    * Added: Hide Offline chat contacts [idea Collin](good.md)
    * Added: Hide "Search, add, or invite" box in chat
    * Improved: Row highlighting in Contacts
    * Improved: Keyboard navigation support for row highlighting [idea Louie](good.md)
    * Improved: Added columns in the options form to keep the page from getting too long
> == 1.1.6
    * Improved: Icons updated
    * Improved: Web Store promotional material updated
    * Improved: Web Store screenshots updated
> == 1.1.5
    * Added: Hide top of nav
    * Added: Hide Mail link
    * Added: Hide Contacts link
    * Added: Hide Tasks link
    * Added: Hide "more" link
    * Added: Update notifications system
    * Improved: Redesigned options page
    * Improved: Working mailto script
> == 1.1.4
    * Added: Custom logo support
    * Added: Row highlighting with custom colors
    * Added: Hide header
    * Added: Hide search
    * Added: Hide mail search
    * Added: Hide star icons
    * Added: Hide chat statuses
    * Added: Send using gmail [mailto:]. Needs more testing, will be fully functional in next release
> == 1.1.3
    * Added: Hide chat [chats still come through](incoming.md)
    * Added: Minimalist for Gmail options shortcut in URL bar [be disabled in options](can.md)
> == 1.1.2
    * Improved: Web store screenshots
    * Improved: Web store description formatting
    * Improved: Options page highlighting on update [only appear when features are added](will.md)
    * Fixed: Conflicts with labs [Side chat & Apps Search](Right.md)
> == 1.1.0
    * Added: Screenshots in options page
    * Improved: Options page organization tweaked
    * Improved: Instructions to hide chat
> == 1.0.0
    * First!**


## CREDITS ##

> Most of Minimalist for Gmail is written from the ground-up but some things are just perfect already:
  * mailto script by Julien Couvreur
  * favicon unread counter by Peter Wooley
> Full details on the About page: http://www.anselsantosa.com/sites/MinimalistGmail/options.html#abo

## LEGAL ##

> I am not a Google Employee or officially affiliated with Google in any way. This extension is not endorsed by Google.
> Google, Gmail, and the Gmail logo are trademarks of Google Inc.
> Use of these trademarks is subject to Google Permissions.

> All bundled scripts are copyright of their original authors.

> I am not, nor is my extension related to "Minimalist Gmail By Matt Constantine" http://mattconstantine.com/mg/