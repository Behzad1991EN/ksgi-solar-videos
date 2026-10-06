# Seasonal solar-production videos

[Open the public video gallery](https://behzad1991en.github.io/ksgi-solar-videos/)

16 separate MP4 clips: one power video and one cumulative generated-energy video for each date.
All clips are silent, 30 seconds, 1920 x 1080, 30 fps.

This repository contains the public KSGI gallery for comparing fixed-tilt and tracker solar production.

Open index.html to browse and play matching pairs, or open any MP4 directly. The gallery works on GitHub Pages with the main branch and root folder as its source. All videos are included in the repository, and the gallery does not require an account.

| Season | Date | Fixed generated energy (kWh) | Tracker generated energy (kWh) | Display window |
|---|---|---:|---:|---|
| Spring | 10 April | 6,520.85 | 8,387.81 | 05:30–19:00 |
| Spring | 10 May | 5,486.97 | 7,494.66 | 04:45–19:24 |
| Summer | 10 July | 6,527.57 | 9,815.05 | 04:37–19:30 |
| Summer | 10 August | 6,537.69 | 8,931.44 | 04:59–19:28 |
| Autumn | 10 October | 5,858.90 | 6,436.55 | 05:46–18:04 |
| Autumn | 10 November | 1,652.00 | 1,744.82 | 06:30–16:58 |
| Winter | 10 January | 3,176.88 | 2,876.43 | 06:59–17:30 |
| Winter | 10 February | 5,233.79 | 5,165.42 | 06:39–18:06 |

Fixed: blue. Tracker: orange. Both dots represent the same simulation time.
Each clip maps that day's observed production interval, with 30-minute margins before and after, linearly to 30 seconds.
Production boundaries are based on positive output; astronomical sunrise/sunset are not separately verified.
Power comes directly from one-minute E_Grid samples. Energy accumulates each positive kW sample divided by 60; negative standby consumption is excluded.
Common scales: power up to 1,000 kW; energy up to 10,000 kWh.
Location: Alborz Province, Iran. Approximate locality coordinates: 35.9646 N, 50.5811 E.
Times use inferred Iran standard time, UTC+03:30.
Source simulations use synthetic Meteonorm weather.
Sources: Yearly/Fixed Tilt Year round simulation Report.CSV and Yearly/Tracker Information.CSV.
