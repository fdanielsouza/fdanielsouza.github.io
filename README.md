[Privacy Policy](/PRIVACY)

# multiInfoCards Power BI Custom Visual

This page is intended to provide support and relevant information about the development process of the visual. 

<h2 style="color:red;font-weight:bold;">Important Warning</h2>
<p style="color:red;">Hello folks! Over the last few months I'm receiving some complaints about some bugs in the formatting options (specially Conditional Formatting pane not showing up) of this visual in Power BI Desktop. I'm aware of the problem, which is caused by the new Power BI Desktop UI, and I'm trying to solve it. However, I can't fix it right now because the custom visual debuging happens in Power BI Service, which is still using the old UI. I already contacted Microsoft about this but I'll need them to update the entire Service, so it can take more time than I expected.</p>
<p style="color:red;">Right now the only workaround is to edit the report in the Service and add Conditional Formatting from there, then save the report again</p>

## How to use the visual

Add a category field in Titles and either an image field in Images or a measure in Informations. The visual can show up to 16 measures. Also you can include measures in Tooltips field to show in a default Power BI tooltip, or use the Report Page canvas tooltip. You can classify data by any value in the visual, cross-filter or highlight data in the same way the official Power BI visuals do, and multiselect using ctrl. Set a value for the individual cards width and customize background and texts with the options provided. If you need to transform numeric values to a display units format, you will need to first remove any formatting from your fields, otherwise the column/measure format should prevail. 

## Current version

1.2.9.0

## Changelog

#### Oct 7, 2021
* Now the visual supports a total of 16 measures
* Added text alignment options for titles, field names and values

#### Oct 4, 2021
* Added a functionality where a user can click on the text of a Web URL formatted measure and it will open the url page

#### Sep 21, 2021
* Implemented support for line breaks inside information texts

#### May 18, 2021
* Added conditional formatting to background and new "cover" mode for images

## Roadmap

* Create a certifiable version of the visual, without features which can call external url services

## Sample report

Take a look at the visual in action with a sample report about COVID-19 data

<figure class="video_container">
  <iframe src="https://app.powerbi.com/view?r=eyJrIjoiZTFhZjIyZDctNTZhZS00YTk3LTlkYzgtNmRlMjkwYjI1YWJmIiwidCI6ImI1OTFhZTU0LTMzYzItNDU4OS1iZTY2LTkwMjFhNDE5NmM3YyJ9&pageName=ReportSection" frameborder="0"  width="100%" height="460" allowfullscreen="true"> </iframe>
</figure>


## Contact for support

[My LinkedIN Profile](https://www.linkedin.com/in/francisco-daniel-souza-fernandes-a75b97b1/)

[My email](mailto:f.daniel.souza@alu.ufc.br)

