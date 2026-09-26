REPLACEABLE WEBSITE COVER IMAGES
================================

These 4 images are TEMPORARY PLACEHOLDERS.
Replace any file with your own .jpg using the SAME filename,
and the website updates automatically. No code changes needed.

Shown on:  Completed Work So Far  ->  01 - WEBSITES

  salonimg.jpg    ->  Glow Box Salon Patna   (glowboxsalonpatna.vercel.app)
  gymimg.jpg      ->  Hercules Health Club   (www.herculeshealthclub.in)
  cafeimg.jpg     ->  Wintbez Cafe           (wintbezcafe.vercel.app)
  schoolimg.jpg   ->  Bol Baby Bol School    (bolbabybolschool.vercel.app)

RULES
-----
1. Keep the filename EXACTLY the same (lowercase, .jpg, no spaces).
2. Keep the file in this folder: /public/website-covers/
3. Any JPG works. These are displayed at 16:10 (e.g. 1600x1000) with
   object-fit: cover, so that ratio avoids any cropping.
4. Do not rename, move, or add suffixes - the code references these
   exact paths, e.g. /website-covers/salonimg.jpg

RELATED FOLDERS
---------------
/public/portfolio-assets/   the 12 swappable DESIGN images
/public/images/             site artwork + the original cover designs,
                            which are kept here untouched as a backup

REGENERATING
------------
If any placeholder image ever goes missing, run from the project root:

    bash tools/restore-assets.sh

That recreates all 16 swappable placeholders plus the original covers.
