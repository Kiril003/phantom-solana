# Image credits

The app screens in this folder (banner, social preview, app-*.jpg) are design previews of the next build with demo data. The photos inside them are third-party works under the licences below; the repository licence does not cover them.

All images are real photographs (no AI images), taken from Wikimedia Commons under the licences below.
Files in `(screen asset) ` were cropped and resized only (ImageMagick); a seen Moment tile is also dimmed to 78% by CSS.
Portraits are Unsplash photos re-published on Commons under CC0. Names in the screens (Olena, Petro, Ana, Taras...) are
demo names; they do not identify the people in the photos.

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Olena avatar (01 chat row, 02 With + guests, 03 Between friends) | (screen asset) av-hat.jpg | CC0 | Allef Vinicius | https://commons.wikimedia.org/wiki/File:Smiling_woman_(Unsplash).jpg |
| Petro avatar (02 With + guests, 03 Between friends) | (screen asset) av-smile.jpg | CC0 | michael (m_minimal) | https://commons.wikimedia.org/wiki/File:Always_smile_(Unsplash).jpg |
| own avatar "you" (top bar on 01-03, 02 guests) | (screen asset) av-curly.jpg | CC0 | Jeremy Bishop | https://commons.wikimedia.org/wiki/File:Curly_hair_and_freckles_man_(Unsplash).jpg |
| Ana avatar (01 chat row) | (screen asset) av-brunette.jpg | CC0 | Christopher Campbell | https://commons.wikimedia.org/wiki/File:Brunette_woman_portrait_(Unsplash).jpg |
| Taras avatar (03 activity row) | (screen asset) av-stockholm.jpg | CC0 | Yingchou Han | https://commons.wikimedia.org/wiki/File:Stockholm_man_with_headphones_(Unsplash).jpg |
| Mum avatar = her cat (01 chat row) | (screen asset) av-mum-cat.jpg | CC0 | 0x0077BE | https://commons.wikimedia.org/wiki/File:Ruby_-_Bicolor_cat_on_windowsill.jpg |
| Friday pho group avatar (01), Place thumb (02), plan card photo (02) | (screen asset) av-pho.jpg, (screen asset) pho-bowl.jpg | CC BY-SA 3.0 | Codename5281 | https://commons.wikimedia.org/wiki/File:Ph%E1%BB%9F_b%C3%B2,_C%E1%BA%A7u_Gi%E1%BA%A5y,_H%C3%A0_N%E1%BB%99i.jpg |
| October trip group avatar (01, row below the fold) | (screen asset) av-trip.jpg | CC BY 4.0 | Andrew Parlette | https://commons.wikimedia.org/wiki/File:Siena_Streets_at_Night.jpg |
| Moment, Olena (01) | (screen asset) mo-bread.jpg | CC BY 4.0 | Agelaia | https://commons.wikimedia.org/wiki/File:Sourdough_Bread_Loaf.jpg |
| Moment, Mum (01) | (screen asset) mo-hills.jpg | CC BY-SA 4.0 | Evanova2023 | https://commons.wikimedia.org/wiki/File:Autumn_and_a_cow_in_the_Beskydy_mountains.jpg |
| Moment, Taras (01) | (screen asset) mo-dog.jpg | CC BY-SA 4.0 | AthaleyahWolf | https://commons.wikimedia.org/wiki/File:Cute_Dog_in_Leaves.jpg |
| Moment, Iva (01, partly visible) | (screen asset) mo-cyclist.jpg | CC0 | Wilfredor | https://commons.wikimedia.org/wiki/File:Cyclist_on_a_Quebec_City_street_in_autumn.jpg |
| Mill Lane Coffee row thumb (03) | (screen asset) th-latte.jpg | CC0 | Londonjackbooks | https://commons.wikimedia.org/wiki/File:Latte_art_heart_Garden_Caff%C3%A9_Portugal_20190118.jpg |

Fonts: Manrope (SIL OFL 1.1), local woff2 in `src/fonts/` (from @fontsource), embedded in each HTML.
Icons: hand-drawn 24 px stroke paths in the Lucide style (Lucide is ISC-licensed).

Rebuild: `bash src/render.sh` (assembles `src/parts/*.html` + `src/base.css` + `(screen asset) ` into self-contained
`src/<NN>-<screen>.html`, then renders `<NN>-<screen>.png` with headless Chromium at 390x844 @2x).

## 08 You, 09 Circle

Reused from the table above: av-curly (own profile photo, 96), av-hat, av-smile, av-brunette, av-stockholm, av-mum-cat
(circle facepiles on 08, member rows on 09). New files below were cropped and resized only (ImageMagick, 240x320).

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Your moment "Today" (08) | (screen asset) mo-park.jpg | CC BY-SA 4.0 | Dietmar Rabich | https://commons.wikimedia.org/wiki/File:D%C3%BClmen,_Wildpark_--_2014_--_3808.jpg |
| Your moment "Tue" (08) | (screen asset) mo-cappuccino.jpg | CC BY 3.0 | Frettie | https://commons.wikimedia.org/wiki/File:Cappuccino_with_latte_art_on_Coffee_Right_in_Brno,_Brno-City_District.jpg |
| Your moment "Sun" (08) | (screen asset) mo-forest.jpg | CC BY-SA 4.0 | Pudelek | https://commons.wikimedia.org/wiki/File:Silesian_-_Moravian_Beskids_in_autumn_2015.JPG |
| Your moment "3 Oct" (08) | (screen asset) mo-streets.jpg | CC BY 4.0 | Andrew Parlette | https://commons.wikimedia.org/wiki/File:Siena_Streets_at_Night.jpg |
| Your moment "1 Oct" (08, cut by the edge) | (screen asset) mo-tram.jpg | CC BY-SA 4.0 | Oleksandr Dede | https://commons.wikimedia.org/wiki/File:Ostrava_historic_tram_Nr._94.jpg |
| Your photo message "from saturday's walk" (04, 05) | (screen asset) ph-forest.jpg | CC BY-SA 4.0 | Pudelek | https://commons.wikimedia.org/wiki/File:Silesian_-_Moravian_Beskids_in_autumn_2015.JPG |
| Friday pho chat (04, 05): group avatar, plan card photo, Olena/Petro/you avatars | reuse of (screen asset) av-pho.jpg, pho-bowl.jpg, av-hat.jpg, av-smile.jpg, av-curly.jpg | see rows above | | |

## 10 Create, 11 Add person

No new downloads. 10 shows the 01 Today render (`(screen asset) under-today.jpg`, a JPEG of `01-today.png`) under the sheet scrim;
11 shows it too, dimmed. Reused: av-curly (your photo in the QR card on 11). New crops below were made with ImageMagick
(crop + resize to 160x160) from files already credited in `design-v2/CREDITS.md`. Names on 11 (Mila Brandt, Milan Horvat,
Mila Sørensen) are demo names and do not identify anyone. The QR on 11 is a real code for `https://phantom-os.dev/i/maxkoval`
(qrencode 4.1.1, level M), decoded back with zbarimg.

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Mila Brandt avatar (11 search result) | (screen asset) av-cup.jpg | CC BY 2.0 | Shixart1985 | https://commons.wikimedia.org/wiki/File:A_hand_reaches_for_a_cup_of_coffee.jpg |
| Milan Horvat avatar = his cat (11 search result) | (screen asset) av-cat-sofa.jpg | CC0 | Sonkiki | https://commons.wikimedia.org/wiki/File:Cat-sleeping-curled-up.jpg |

## 06 Map, 07 Place

New files below were cropped and resized only (ImageMagick). Reused: av-curly (your photo), av-hat (Olena), av-brunette (Ana),
av-stockholm (Taras), th-latte (flat white on 07). Marta is a demo name and does not identify the person in the photo.

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Marta avatar (06 map pin and sheet) | (screen asset) av-marta.jpg | CC0 | REASONS ART (reas) | https://commons.wikimedia.org/wiki/File:Smiling_woman_in_blanket_(Unsplash).jpg |
| Mill Lane Coffee hero photo (07) | (screen asset) pl-millane.jpg | CC0 | Joanna Boj | https://commons.wikimedia.org/wiki/File:Cook_in_a_caf%C3%A9_(Unsplash).jpg |
| Cinnamon bun thumb (07) | (screen asset) th-cinnamon.jpg | CC0 | Andy Li | https://commons.wikimedia.org/wiki/File:Cinnamon_roll_-_Clifton_Road_Coffee_2026-03-17.jpg |
| Avocado toast thumb (07) | (screen asset) th-avotoast.jpg | CC0 | Andy Li | https://commons.wikimedia.org/wiki/File:Smashed_Avocado_on_Sourdough_Toast_with_Chai_Latte_-_M%26S_cafe_2023-08-08.jpg |

Map (06): drawn by our own script from OpenStreetMap data (OSM API 0.6 map call, 8 Oct 2026), © OpenStreetMap contributors,
ODbL 1.0 (https://www.openstreetmap.org/copyright). Geometry is real; street and place names on the map are neutral demo names,
so the screen names no city. Marta's walk is the shortest path on the real street graph (340 m). The SVG is inlined in
`src/parts/06-map.html`; rebuild 06/07 with `python3 -I build.py` as for the other screens.

## 14 Moment, 15 Language

14 reuses av-hat.jpg (Olena). The full-size moment photo is a new crop of the same Commons file as the Today tile, made with
ImageMagick (resize + centre crop to 780x584) from `design-v2/(screen asset) dirA/bread.jpg`. 15 has no photos and no flags (removed in the final pass: rows are text only); the logo mark is redrawn from
`showcase-out/nightpost-logo-512.png`.
Manrope Cyrillic (SIL OFL 1.1, @fontsource) is embedded on 15 for "Українська" (`src/fonts/manrope-cyrillic-{400,500,600}.woff2`).

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Olena's moment, full screen (14) | (screen asset) mo-bread-lg.jpg | CC BY 4.0 | Agelaia | https://commons.wikimedia.org/wiki/File:Sourdough_Bread_Loaf.jpg |

## 12 Group, 13 Call

Reused: av-smile (Petro), av-brunette (Ana), av-stockholm (Taras) on 12; av-hat (Olena, caller) on 13 and 13-call-compact,
plus every image of 01 Today on 13-call-compact (it is the Today screen during a call). New files were cropped and resized only (ImageMagick, 240x240).

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| "Cabin weekend" group photo (12) | (screen asset) g12-cottage.jpg | CC BY-SA 4.0 | Νικόλαος Κυριακάκης | https://commons.wikimedia.org/wiki/File:Summer_cottage,_Finland.jpg |
| Shared media 1, lake (12) | (screen asset) g12-lake.jpg | CC BY 2.0 | RichardBH from Hamilton, Canada | https://commons.wikimedia.org/wiki/File:Shadow_Lake_Morning_(6101617998).jpg |
| Shared media 2, campfire (12) | (screen asset) g12-campfire.jpg | CC BY 2.0 | vastateparksstaff | https://commons.wikimedia.org/wiki/File:Campfire_at_Twin_Lakes_State_Park_(14428686324).jpg |
| Shared media 3, trail (12) | (screen asset) g12-trail.jpg | CC BY-SA 4.0 | Harshit | https://commons.wikimedia.org/wiki/File:Hike_trail_in_Hunneberg_in_autumn.jpg |
| Shared media 4, bridge (12) | (screen asset) g12-bridge.jpg | CC0 | Zach Remick | https://commons.wikimedia.org/wiki/File:Hiking_Trail_Bridge_(253965407).jpeg |

## 16 Assistant

No new downloads. Reused from the tables above: av-smile, av-brunette, av-stockholm (facepile of
friends free on Saturday; the top bar now shows a gift icon, not Olena's photo), pl-millane (Mill Lane Coffee photo in the "Table for 7" step). Rebuild with `python3 -I build.py`.

## Final pass (director's fix list, 8 Oct 2026)

No new downloads. Four new avatar crops were made (ImageMagick, centre crop + resize to 240x240) from Commons files already
fetched for this set; the full moment photo on 14 is a new crop of the sourdough file credited above. Names are demo names and
do not identify the people in the photos.

| Used as | File | Licence | Author | Source |
|---|---|---|---|---|
| Milan Horvat avatar (11), replaces the cat | (screen asset) av-milan.jpg | CC0 | Seth Doyle | https://commons.wikimedia.org/wiki/File:Man_vanguard_glasses_outdoors_(Unsplash).jpg |
| Friends facepile, third face (08) | (screen asset) av-kofi.jpg | CC0 | William Stitt | https://commons.wikimedia.org/wiki/File:Face_portrait_(Unsplash).jpg |
| Iva, Work facepile (08) | (screen asset) av-iva.jpg | CC0 | Brooke Cagle | https://commons.wikimedia.org/wiki/File:Smiling_woman_by_a_window_(Unsplash_NoRsyXmHGpI).jpg |
| Study facepile, second face (08) | (screen asset) av-lina.jpg | CC0 | Ehimetalor Unuabona | https://commons.wikimedia.org/wiki/File:Woman_in_glasses_smiling_(Unsplash).jpg |
| Olena's moment, full screen (14), replaces mo-bread-lg | (screen asset) mo-bread-full.jpg | CC BY 4.0 | Agelaia | https://commons.wikimedia.org/wiki/File:Sourdough_Bread_Loaf.jpg |

Where images are used now (supersedes the screen lists in the tables above):
- av-marta (Marta): 06, 08 (Close and Travel facepiles), 09 (member row).
- g12-cottage (Cabin weekend): 12 header, and the Cabin weekend chat row on 01 (below the fold) and 13-call-compact.
- av-hat (Olena): 01-09, 13, 13-call-compact, 14; no longer on 16.
- av-mum-cat (Mum): 01, 08 (Close facepile), 13-call-compact.
- under-today.jpg is regenerated from the final 01 render (backdrop of 10 and 11).
- No longer used anywhere and can be deleted: av-cat-sofa.jpg (Milan now has a portrait), mo-bread-lg.jpg (replaced by
  mo-bread-full.jpg), ph-forest.jpg (the photo message on 04/05 was removed to make room for the bill card).
