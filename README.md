# KSGI solar-production video gallery

[Open the public video gallery](https://behzad1991en.github.io/ksgi-solar-videos/)

58 separate 30-second, silent, 1080p MP4 videos compare fixed-tilt and tracker systems.

Choose one of four navigation tabs: Yearly, Seasonal, Monthly, or Sample Days. Each section shows its own options: the complete year, four seasons, twelve months, or one sample date per month (the 10th). Only the chosen section and its selected video pair are displayed. Choices are remembered when switching sections. Each view has a power video and a generated-energy video.

The Season and Days dropdowns use matching seasonal colours: Spring light green, Summer light red, Autumn light orange, and Winter light gray.

## Yearly, seasonal and monthly views

| View | Days | Fixed energy (MWh) | Tracker energy (MWh) | Range |
|---|---:|---:|---:|---|
| Yearly | 365 | 1,938.35 | 2,342.09 | January - December |
| Spring | 93 | 544.10 | 727.66 | 20 March - 20 June |
| Summer | 93 | 579.25 | 790.60 | 21 June - 21 September |
| Autumn | 90 | 419.42 | 424.24 | 22 September - 20 December |
| Winter | 89 | 395.58 | 399.60 | 21 December - 19 March |
| January | 31 | 128.83 | 118.53 | 1 - 31 January |
| February | 28 | 137.44 | 140.73 | 1 - 28 February |
| March | 31 | 168.98 | 194.71 | 1 - 31 March |
| April | 30 | 170.05 | 213.97 | 1 - 30 April |
| May | 31 | 184.06 | 254.00 | 1 - 31 May |
| June | 30 | 183.89 | 266.54 | 1 - 30 June |
| July | 31 | 192.80 | 275.34 | 1 - 31 July |
| August | 31 | 197.05 | 268.97 | 1 - 31 August |
| September | 30 | 184.56 | 225.29 | 1 - 30 September |
| October | 31 | 161.53 | 172.89 | 1 - 31 October |
| November | 30 | 117.35 | 110.90 | 1 - 30 November |
| December | 31 | 111.82 | 100.21 | 1 - 31 December |

Power is the mean of all 1,440 one-minute grid-output kW samples in each day, including standby imports. The seasonal average curves show these daily means across the whole season, not a representative month.
Energy sums each positive one-minute kW sample divided by 60 and accumulates those daily energies across the selected period. Longer-period energy is displayed in MWh. Standby imports are excluded from generated energy.
The curves are continuous lines through the daily aggregates. The moving dots use linear interpolation. The full period maps linearly to 30 seconds.

The yearly axis has month labels; seasonal axes have spaced dates; monthly axes have day-of-month labels. Spring: 20 March–20 June; Summer: 21 June–21 September; Autumn: 22 September–20 December; Winter: 21 December–19 March. Winter proceeds from December through January, February and March.

## Individual dates

| Season | Date | Fixed energy (kWh) | Tracker energy (kWh) |
|---|---|---:|---:|
| Spring | 10 April | 6,520.85 | 8,387.81 |
| Spring | 10 May | 5,486.97 | 7,494.66 |
| Spring | 10 June | 6,345.26 | 9,207.55 |
| Summer | 10 July | 6,527.57 | 9,815.05 |
| Summer | 10 August | 6,537.69 | 8,931.44 |
| Summer | 10 September | 5,996.59 | 7,574.87 |
| Autumn | 10 October | 5,858.90 | 6,436.55 |
| Autumn | 10 November | 1,652.00 | 1,744.82 |
| Autumn | 10 December | 4,238.36 | 3,744.71 |
| Winter | 10 January | 3,176.88 | 2,876.43 |
| Winter | 10 February | 5,233.79 | 5,165.42 |
| Winter | 10 March | 6,600.21 | 7,476.74 |

The twelve individual-day views use one-minute power curves and cumulative generated-energy curves, including 30-minute margins before and after production.

Fixed is blue; Tracker is orange. Location: Alborz Province, Iran. Approximate locality coordinates: 35.9646 N, 50.5811 E. Times use inferred Iran standard time, UTC+03:30.
Sources are PVsyst simulations using synthetic Meteonorm weather: Yearly/Fixed Tilt Year round simulation Report.CSV and Yearly/Tracker Information.CSV. Each plant has 525,600 validated one-minute samples covering 365 days. Monthly and seasonal energy totals reconcile to the yearly total.
