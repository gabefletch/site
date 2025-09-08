# Changes to The Gabe Fletcher Landing Page
Note that this changelog begins with v4.0 and no data before this sequential version exists as v4.0 is the first version to be hosted on a service that allows for code exporting.<br>

[Jump to Oldest Changes](https://github.com/gabefletch/site/blob/main/changes.md#v40)

## v8.1.4
8 September 2025
- Fixes the "Message Me" button not functioning properly on certain devices
- Implements Framer's new Rolldown Bundler system

## v8.1.3
15 August 2025
- Backend implementations for future site updates; no front-facing changes made

## v8.1.2
10 August 2025
- Adds the Utilities page and card to the Projects section
- Adds the "Arrow" utility

## v8.1.1
23 July 2025
- Fixes typeface inconsistencies on certain pages
- Fixes the "Made in Framer" badge being displayed for a brief period
- Fixes the top navigation bar on the homepage having a redundant option on desktop for a brief period after migrating backend site data

## v8.1
22 May 2025
- Changes sitewide typeface from San Francisco Pro Display to IBM Plex Sans (icons are still using SF Symbols)
- Changes top banner color to pure white
- Adds a new "/links" page with a list of official links
- Adds a new "/images" page for image attribution information, accessed via the bottom of the home page, replacing the previous simple attribution text and link

## v8.0.1.3
20 May 2025
- Adds Back to Pop Podcast card to "Projects" section

## v8.0.1.2
10 April 2025
- Adds Bandcamp support and buttons on the Somniate portion of the site

## v8.0.1.1
9 March 2025
- Fixes an issue where tapping "Gabe." in the top navigation bar on mobile would have no action, whereas clicking it on desktop directs back to the root domain
- Slightly changes the wording of some cards in the "Skills" section to be more concise and align with industry terminology
- Implements small backend optimizations (Cloudflare)

## v8.0.1
3 March 2025
- Integrates small cosmetic changes

## v8.0
1 March 2025
- Integrates updated interface styling and new Contact interface
- Migrates site to gabefletcher.net from gabefletch.me (old domain will redirect)

## v7.3
11 December 2024
- Integrates Cloudflare DNS
- Updates the appearance and images used in the "About" section
- Updates the "Contact" section to feature a direct "mailto:" email protocol button
- Integrates a vanity email address, replacing the previous Gmail hosted address

## v7.2
7 November 2024
- Updates Gabe icon branding and navbar coloration to match
- Fixes an issue where Deltablock FAQ accordians would render incorrectly on the mobile breakpoint
## v7.1.7.1
15 October 2024
- Updates album cover images on the following pages:
  - `/somniate/releases`
  - `/somniate/releases/self`
  - `/somniate/releases/vos-deluxe`
- Fixes an issue where some Somniate related pages had incorrect tab titles
## v7.1.7
15 October 2024
- Implements a redesigned version of the "Gabe Fletcher is..." text cycle animation to fix issues where snapping back to the beginning of the animation cycle would be noticable when viewing on certain browsers/devices
- Updates the animation styling of the text cycle to take longer between text strings (now 2s instead of 1.5s)
- Adds more text strings to the text cycle
- Significantly reduces animations present when scrolling to be less distracting
- Adjusts some image rendering effects to be less distracting
- Adjusts the spacing of the "Projects" section on the mobile breakpoint to be more consistent with site-wide element spacing
- Implements more Z axes layers (up to 5) to assist with the new text cycle implementation
- Adjusts the hamburger menu button on the mobile breakpoint to have a bolder icon for consistency with site-wide button design
## v7.1.6.1
6 October 2024
- Fixes an issue on `/somniate/releases` where the "Listen" button was layered above the top nav bar, causing unintended overlapping when scrolling, navbar Z position is now set to 2 rather than 1
## v7.1.6
6 October 2024
- Re-adds the `/releases` page to `/somniate`
- Adds `/releases/self` and `/releases/vos-deluxe` pages with album art and links to streaming services
  - Adding in-line playback to these pages is planned in the future; a solution for hosting and/or fetching tracks with a streamable URL needs to be found since uploading is restricted by having a Framer Pro plan
- Fixes an issue where the version string displayed in `/deltablock/install` did not match `/deltablock`
## v7.1.5.1
22 September 2024
- Fixes some non-major backend issues with link directing
## v7.1.5
19 September 2024
- Adds redesigned FAQ accordion section for `/deltablock` that does not rely on a CMS collection for functionality
- Adds some additional questions to the FAQ section of `/deltablock`
- Adds additional scroll animations to the FAQ section of `/deltablock` for consistency with other page elements
- Adjusts `/deltablock` to reflect the release of DeltaBlock v2.4
- Obscures Optimal v11 related page slugs to prevent user access during development phase
## v7.1.4
18 September 2024
- Adjusts the GitHub button on the GFLP to direct straight to this changelog page instead of the top of the repository
- Fixes an issue where clicking "Get Started" on the desktop breakpoint of `/deltablock` opens the `/deltablock/install` page in a new tab instead of the same tab
- Fixes an issue where the `/deltablock/install` page showed an incorrect Tab Title
## v7.1.3
18 September 2024
- Fixes the "Projects" section header being center justified on the mobile breakpoint when this was inconsistent
- Fixes an issue where the "Projects" button in the navbar would not smooth-scroll to the "Projects" section
- Adjusts some button styling from elements carried over from v6 to match the v7 styling
- Adds 26px of padding to all mobile breakpoint footers not adjusted by v7.1.1:
  - `/deltablock`, `/deltablock/install`, and `/somniate`
- Fixes an issue where footer text on the mobile breakpoint of `/somniate` was not properly centered
## v7.1.2
18 September 2024
- Fixes an issue where tapping "Back" on the mobile breakpoint of `/deltablock` would direct to the GF landing page instead of the DB home
- Fixes an issue where tapping "Contact" on the mobile breakpoint of the GF landing page in the hamburger menu would open a new tab to the Contact section rather than closing the menu and smooth-scrolling to the section
- Attempts to fix an issue where some text effects may rarely have overlap issues near the edges of their rendering frames
## v7.1.1
18 September 2024
- Fixes several button links on the mobile breakpoint of the `/deltablock` page directing to incorrect locations
- Attempts to fix an issue where using the hamburger menu on mobile would close the menu without scrolling to a section when tapping a menu item
- Adds 26px of padding to the bottom of the footer on the mobile breakpoint
## v7.1
17 September 2024
- Replaces "Projects" section with an updated version of the section from v6.1.2
## v7.0
17 September 2024
- Introduces a complete sitewide redesign with unified UI across all pages and subpages based on Subscribfy UI
## v6.1.2
11 July 2024
- Fixes some element radii not being the same value across all breakpoints
## v6.1.1
9 July 2024
- Fixes changelog entry for v6.1 not being pushed on GitHub
- Fixes some spelling errors present on `/deltablock`
- Fixes the "a project by Gabe Fletcher" link on `/deltablock` directing to a deprecated version of the Gabe Fletcher home page
## v6.1
6 July 2024
- Slightly alters interface styling
- Removes all references to Optimal on home page
- Replaces Optimal with Instagram content section under the 'Projects' section
## v6.0.2
19 April 2024
- Pushes SF Pro Display and SF Symbols to v5 across all pages and subpages
## v6.0.1
16 April 2024
- Site will no longer have animated elements if the user visiting has enabled reduced motion on their browser or OS
- Favicon updated
- Apple Touch Icon and Google Search Icons updated
## v6.0
4 April 2024
- Complete interface redesign
- All element ordering and link directivity remains the same
## v5.4.1.1
1 April 2024
- Fixes the 404 page "Go Back Home" button directing to the "Oops Wrong Domain" placeholder; caused after transition to gabefletch.me from gabe.framer.website
## v5.4.1
28 March 2024
- Updates width parameters for the SGA10e breakpoint for consistency with width for other elements
## v5.4
27 March 2024
- Integrates new DeltaBlock branding and site slug "/deltablock"
- Adds the SGA10e breakpoint to major pages across mutliple slugs for better viewing on narrower mobile devices
## v5.3.2
15 March 2024
- Adds Somniate Records section
- Site is now Framer Basic rather than Framer Mini, allowing more subpages
## v5.3.1.1
5 March 2024
- Fixes the "Listen Now" button linking to nowhere on certain breakpoints
- Backend optimizations
## v5.3.1
29 February 2024
- Alters squared image resolutions across the site to proper matched square resolution
- Alters the Visions of Space EP image to have a border on the image file rather than rendering a border around it via CSS.
## v5.3
29 February 2024
- Changes site-wide color background to a darker blue for better accent color readability
- Adds the Music section and the Visions of Space EP section
- Changes button styling to outline rather than solid
- Adds gaussian blur to nav bar icon while site elements are rendered behind it
- Adds contextual icons to each section via SF Symbols
- Changes site-wide font to SF Pro Display
- Adds the same contextual icons to the nav menu
- Adds the Music section to the nav menu
- Reformats section slug naming to be more consistent with their actual naming on the site
## v5.2
18 January 2024
- Further alters site color scheming to an all-blue style to better match new social branding and avoid eye-strain possible by the color scheme present in v5.1
- Alters spacing of the side menu to be more concise
- Alters some text elements to bold text for better user experience
- Alters all button colors to be consistent
- Alters all body text to be solid white rather than light grey
- Adjusts width of the "+" navbar icon to be thicker for more consistency with other buttons
- Implements a "+" to "x" animation for the navbar icon when opening/closing the navbar
- Backend optimizations
## v5.1
11 January 2024
- Alters site color scheming to match new social branding
- Slightly alters some text to be more concise
## v5.0.4
24 December 2023
- Adds an "Upcoming Work / Appearances" section between the "About" and "Web Projects" sections. 

## v5.0.3.4
11 December 2023
- Updates the Optimal image card to match with the new upcoming Optimal v11 launch branding.

## v5.0.3.3
1 December 2023
- Fixes some backend issues

## v5.0.3.2
30 November 2023<br>
- Fixes an issue where "Visit" buttons under the Web Projects section failed to link anywhere on larger desktop displays.

## v5.0.3.1
29 November 2023<br>
- Slightly alters the text underneath "Let's Talk" to be more concise.

## v5.0.3
27 November 2023<br>
- Adds a styled 404 page instead of Framer's default 404 page.

## v5.0.2
26 November 2023<br>
- Fixes the most recent site version string not appearing across all device rendering schemes.

## v5.0.1
26 November 2023<br>
- Revises the description of the DeltaBlock section to properly style NextDNS as "NextDNS" instead of "Next DNS."
- Re-adds the "Screenshots" section to the Readme of this repo.

## v5.0
24 November 2023<br>
- Simplifies, redesigns, and migrates the site to Framer.
- https://gabefletch-old.webflow.io can be used to access the site versions prior to v5.0

## v4.1
26 October 2023<br>
- Adds "#AltCompatibility for Threads" to the "Web Projects" section.
- Updates the footer of the site to reflect the new site version "v4.1 (26 October 2023)"

## v4.0.3.3
9 October 2023<br>
- Fixes "Experience" link on mobile navigation menu linking to the unfinished Experience page on the site rather than the resume document on Google Drive (intended functionality).
- Updates the footer of the site to reflect the new site version "v4.0.3.3 (9 October 2023)"

## v4.0.3.2
19 September 2023<br>
- Alters navigation heading across all breakpoints to have a solid matching dark blue background color so that navigation header elements do not conflict with other elements on the rest of the page.
- Alters navigation heading on the mobile breakpoint to match changes done to the desktop and above breakpoints.
- Alters the mobile navigation selection menu to be a solid matching dark blue background rather than a blur filter of the rest of the page.
- Adds an "Experience" navigation option across all breakpoints leading to "dub.sh/gabe-sound-resume"
- Alters the button text in the "Skills" section from "View My Resume" to "View My Experience." Button link target was not changed.
- Adds "Experience" page to the backend with the `/resume` slug. Page is currently unreachable unless entered directly.
- v4.1 will compliment this update with a finished "Experience" page resembling the currently accessible resume document but as a page on the site instead with more visual appeal and images. The resume document will still be acessible from this new page.
- Updates the footer of the site to reflect the new site version "v4.0.3.2 (19 September 2023)"

## v4.0.3.1<br>
18 September 2023<br>
- Removes the left over `/style` slug page from deployment.
- Alters the footer "GitHub" link to direct to the site repository. The GitHub link in the "About" section will still direct to "github.com/gabefletch" as the footer link did previously.
- Updates the footer of the site to reflect the new site version "v4.0.3.1 (18 September 2023)"

## v4.0.3<br>
8 September 2023<br>
- Corrects sizing, padding, and margin errors on the mobile portrait breakpoint caused by the previous update
- Updates the footer of the site to reflect the new site version "v4.0.3 (8 September 2023)"

## v4.0.2<br>
5 September 2023<br>
- Alters margins and padding across multiple site elements and breakpoints to ensure proper rendering positioning across multiple device types, screen sizes, and aspect ratios
- Alters footer text to be larger on extra large desktop breakpoints for better user experience
- Updates the footer of the site to reflect the new site version "v4.0.2 (5 September 2023)"
- Changes header size of the "note that..." text string on this changelog to be one header version smaller than it was previously to be less prominent and more space efficient
- Cleans up empty lines in this changelog

## v4.0.1
2 September 2023<br>
- Alters link targeting on the "View My Resume" button to use the shortlink "dub.sh/gabe-sound-resume" instead of a raw Google Drive share link
- Updates styling and accuracy of the equipment usage list on the resume
- Updates the footer of the site to reflect the new site version "v4.0.1 (2 September 2023)"

## v4.0
6 August 2023<br>
- Adds version string text to the bottom of the home page; clicking redirects here
- Adds Eagle Scout and Xerox Award section below the "Gabe Fletcher" main header and "Sound Designer and Web Developer Attending Shenandoah Univ." and above the "Sound Designer/Web Developer horizontal animating element.
- Adjusts all section margins site-wide to be less for better user experience.
- Adjusts "Submit" text on Contact form to the same bold weight used on all other buttons for continuity.
- General bug fixes and stability improvements.

[Jump to Newest Changes](https://github.com/gabefletch/site/blob/main/changes.md#changes-to-the-gabe-fletcher-landing-page)
