# solar-panel-feasibility
Repository for analysis and discussion on the feasibility of solar panels.

## How much does the church spend on electricity per year?

Yearly electricity bills for years 2013-2022 are plotted below:

![image](plots/yearly_electricity_bill.png)

Recent fluctuations in electricity prices are evident. (Note for transparency: I didn't have the financial report for 2017, so it is presented as the average of the four years on either side.)

## What do we assume for our calculations?

At present we use quite rough estimates. If anyone sees a figure they disagree with, reach out and we can update it. We can get a better idea of what to expect if we consult a provider. The figures used in the projections are shown below:

```
installation_cost: 17850    # £ including battery storage and maintenance (2 x 10 kWh batteries to account for replacement)
expected_unit_rate: 0.2839  # PowerNI current rate for quarterly bill, £ / kWh
sell_back_rate: 0.1422       # £ / kWh
solar_panel_total_output: 12.75 # kW
solar_panel_lifetime: 25    # years
```

The calculations also rely on meter readings collected through the year, as well as statistics obtained from the [Met Office](https://www.metoffice.gov.uk/research/climate/maps-and-data/uk-climate-averages/gcey2u2yw) for hours of sunshine in Northern Ireland. All this data can be found in [data/meter_readings.xlsx].

## Where can I see the calculations?

All working out is shown in [this notebook](notebooks/best_estimate.ipynb). I've included some further discussion there, and have tried to make everything as clear as possible, but let me know if something doesn't make sense or seems incorrect. 

## What can we conclude?

Based on this rough analysis, it seems that a 4kW solar panel installation would provide an annual saving to the church of around £2800, and would pay for itself in around 6 years. There is uncertainty around this number as this depends on how the church uses the electricity the solar panels generate, as well as on electricity prices.