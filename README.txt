Upload these files directly to the root of your GitHub repo:

- index.html
- daily.html
- weekly.html
- monthly.html
- yearly.html
- .nojekyll

Then in GitHub:
Settings -> Pages
Source: Deploy from a branch
Branch: main
Folder: / (root)

All pages share the same localStorage key:
github-workout-daily-widget-v1


v2 update:
- Weekly/monthly/yearly views now use each day's planned workout count.
- Days with no planned workouts show no count.
- The daily page snapshots planned workouts per day.
- Older data created before this update may not have planned counts saved.


v3 update:
- Weekly view: click any day to plan workouts ahead.
- Daily view: previous day / next day buttons added so you can review or plan around the selected date.
