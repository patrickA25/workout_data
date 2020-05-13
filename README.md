# Workout Project
Over the last two months I have been working out everyday and tracking what type of workout, how long I worked out, and the total calories that I have burned for both the workut and the day. I wanted to learn how to make ajustments to a flat file (workout_data.txt) then push it to Github, and then pull the data into a R session and generate an R-markdown file, and then load the markdown file into my personal website.

## Example of R-markdown document
<center>

Workout Summary  
3/28/2020 to 05/13/2020
================
Patrick Ayers

</center>

## Over View of Project

I have started to make sure I am walking for at least 30 minutes a day,
and I have been doing this since March 28th. This project has two main
goals. First is to have accountability for making sure I am taking a
30-minute walk every day. The second is to create a report that can be
quickly updated daily with minimal effort. I have created a report that
can be updated in a and reposted in just a few moments. I will continue
to update this report, along with possibly making updates to this
document over the coming weeks.

## Top Line Summary of Information

Here is the summary of yesterday’s workout along with average
information about the last 46 days of workouts.

### Yesterdays Workout

<table>

<thead>

<tr>

<th style="text-align:left;">

Date

</th>

<th style="text-align:left;">

Workout Type

</th>

<th style="text-align:right;">

Time

</th>

<th style="text-align:right;">

Average Hear Rate

</th>

<th style="text-align:right;">

Calories Burned

</th>

<th style="text-align:right;">

Distance

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

2020-05-12

</td>

<td style="text-align:left;">

Walk/Strength\_Training

</td>

<td style="text-align:right;">

42

</td>

<td style="text-align:right;">

137

</td>

<td style="text-align:right;">

511

</td>

<td style="text-align:right;">

2.11

</td>

</tr>

</tbody>

</table>

### Averages for Last 46 Workouts

<table>

<thead>

<tr>

<th style="text-align:right;">

Average Workout Time

</th>

<th style="text-align:right;">

Average Calories Burned

</th>

<th style="text-align:right;">

Average Heart Rate

</th>

<th style="text-align:right;">

Average Distance

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:right;">

43.78

</td>

<td style="text-align:right;">

415.9565

</td>

<td style="text-align:right;">

130.5

</td>

<td style="text-align:right;">

2.21

</td>

</tr>

</tbody>

</table>

### Averages for Last 46 Day Information

There are two columns about calories in this table. Average Active
Calories is the average of the total active calories my Apple watch has
at the end of the day. The second column Average Total Calories is the
total number of calories my body burned; this number contains the sum of
my Basal Metabolic Rate (BMR) and the active calories my body has
burned.

<table>

<thead>

<tr>

<th style="text-align:right;">

Average Active Calories

</th>

<th style="text-align:right;">

Average Total Calories

</th>

<th style="text-align:right;">

Average Steps taken

</th>

<th style="text-align:right;">

Average Distance Walked

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:right;">

1036.11

</td>

<td style="text-align:right;">

3884.54

</td>

<td style="text-align:right;">

8523.93

</td>

<td style="text-align:right;">

3.98

</td>

</tr>

</tbody>

</table>

## General Information Over Time

<img src="report_2020-05-13_files/figure-gfm/unnamed-chunk-4-1.png" width="70%" />
<img src="report_2020-05-13_files/figure-gfm/unnamed-chunk-5-1.png" width="70%" />
<img src="report_2020-05-13_files/figure-gfm/unnamed-chunk-6-1.png" width="70%" />
<img src="report_2020-05-13_files/figure-gfm/unnamed-chunk-7-1.png" width="70%" />
<img src="report_2020-05-13_files/figure-gfm/unnamed-chunk-8-1.png" width="70%" />

## Workout Data Table

<table>

<thead>

<tr>

<th style="text-align:left;">

Date

</th>

<th style="text-align:right;">

Time

</th>

<th style="text-align:right;">

Calories Burned

</th>

<th style="text-align:right;">

Average Hear Rate

</th>

<th style="text-align:right;">

Distance

</th>

<th style="text-align:right;">

Total Activity Calories

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

2020-03-28

</td>

<td style="text-align:right;">

55

</td>

<td style="text-align:right;">

542

</td>

<td style="text-align:right;">

147

</td>

<td style="text-align:right;">

3.23

</td>

<td style="text-align:right;">

1003

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-03-29

</td>

<td style="text-align:right;">

55

</td>

<td style="text-align:right;">

583

</td>

<td style="text-align:right;">

144

</td>

<td style="text-align:right;">

3.25

</td>

<td style="text-align:right;">

1052

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-03-30

</td>

<td style="text-align:right;">

55

</td>

<td style="text-align:right;">

567

</td>

<td style="text-align:right;">

137

</td>

<td style="text-align:right;">

3.24

</td>

<td style="text-align:right;">

1146

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-03-31

</td>

<td style="text-align:right;">

61

</td>

<td style="text-align:right;">

538

</td>

<td style="text-align:right;">

127

</td>

<td style="text-align:right;">

3.28

</td>

<td style="text-align:right;">

976

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-01

</td>

<td style="text-align:right;">

22

</td>

<td style="text-align:right;">

171

</td>

<td style="text-align:right;">

125

</td>

<td style="text-align:right;">

1.01

</td>

<td style="text-align:right;">

1174

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-02

</td>

<td style="text-align:right;">

34

</td>

<td style="text-align:right;">

283

</td>

<td style="text-align:right;">

121

</td>

<td style="text-align:right;">

1.72

</td>

<td style="text-align:right;">

806

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-03

</td>

<td style="text-align:right;">

69

</td>

<td style="text-align:right;">

674

</td>

<td style="text-align:right;">

140

</td>

<td style="text-align:right;">

3.83

</td>

<td style="text-align:right;">

1150

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-04

</td>

<td style="text-align:right;">

42

</td>

<td style="text-align:right;">

372

</td>

<td style="text-align:right;">

128

</td>

<td style="text-align:right;">

2.13

</td>

<td style="text-align:right;">

981

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-05

</td>

<td style="text-align:right;">

64

</td>

<td style="text-align:right;">

550

</td>

<td style="text-align:right;">

126

</td>

<td style="text-align:right;">

3.22

</td>

<td style="text-align:right;">

1320

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-06

</td>

<td style="text-align:right;">

30

</td>

<td style="text-align:right;">

245

</td>

<td style="text-align:right;">

111

</td>

<td style="text-align:right;">

0.00

</td>

<td style="text-align:right;">

839

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-07

</td>

<td style="text-align:right;">

36

</td>

<td style="text-align:right;">

340

</td>

<td style="text-align:right;">

133

</td>

<td style="text-align:right;">

0.00

</td>

<td style="text-align:right;">

1131

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-08

</td>

<td style="text-align:right;">

64

</td>

<td style="text-align:right;">

589

</td>

<td style="text-align:right;">

130

</td>

<td style="text-align:right;">

3.48

</td>

<td style="text-align:right;">

1213

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-09

</td>

<td style="text-align:right;">

34

</td>

<td style="text-align:right;">

214

</td>

<td style="text-align:right;">

92

</td>

<td style="text-align:right;">

0.00

</td>

<td style="text-align:right;">

831

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-10

</td>

<td style="text-align:right;">

30

</td>

<td style="text-align:right;">

240

</td>

<td style="text-align:right;">

125

</td>

<td style="text-align:right;">

1.40

</td>

<td style="text-align:right;">

881

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-11

</td>

<td style="text-align:right;">

36

</td>

<td style="text-align:right;">

370

</td>

<td style="text-align:right;">

135

</td>

<td style="text-align:right;">

2.16

</td>

<td style="text-align:right;">

1129

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-12

</td>

<td style="text-align:right;">

28

</td>

<td style="text-align:right;">

299

</td>

<td style="text-align:right;">

126

</td>

<td style="text-align:right;">

0.00

</td>

<td style="text-align:right;">

823

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-13

</td>

<td style="text-align:right;">

27

</td>

<td style="text-align:right;">

236

</td>

<td style="text-align:right;">

135

</td>

<td style="text-align:right;">

1.38

</td>

<td style="text-align:right;">

735

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-14

</td>

<td style="text-align:right;">

39

</td>

<td style="text-align:right;">

343

</td>

<td style="text-align:right;">

120

</td>

<td style="text-align:right;">

2.09

</td>

<td style="text-align:right;">

1160

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-15

</td>

<td style="text-align:right;">

23

</td>

<td style="text-align:right;">

247

</td>

<td style="text-align:right;">

150

</td>

<td style="text-align:right;">

1.36

</td>

<td style="text-align:right;">

830

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-16

</td>

<td style="text-align:right;">

31

</td>

<td style="text-align:right;">

365

</td>

<td style="text-align:right;">

144

</td>

<td style="text-align:right;">

2.00

</td>

<td style="text-align:right;">

1053

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-17

</td>

<td style="text-align:right;">

34

</td>

<td style="text-align:right;">

437

</td>

<td style="text-align:right;">

144

</td>

<td style="text-align:right;">

2.11

</td>

<td style="text-align:right;">

1303

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-18

</td>

<td style="text-align:right;">

33

</td>

<td style="text-align:right;">

273

</td>

<td style="text-align:right;">

118

</td>

<td style="text-align:right;">

1.74

</td>

<td style="text-align:right;">

901

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-19

</td>

<td style="text-align:right;">

27

</td>

<td style="text-align:right;">

250

</td>

<td style="text-align:right;">

143

</td>

<td style="text-align:right;">

1.40

</td>

<td style="text-align:right;">

882

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-20

</td>

<td style="text-align:right;">

40

</td>

<td style="text-align:right;">

355

</td>

<td style="text-align:right;">

123

</td>

<td style="text-align:right;">

2.25

</td>

<td style="text-align:right;">

1001

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-21

</td>

<td style="text-align:right;">

50

</td>

<td style="text-align:right;">

433

</td>

<td style="text-align:right;">

123

</td>

<td style="text-align:right;">

2.56

</td>

<td style="text-align:right;">

976

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-22

</td>

<td style="text-align:right;">

41

</td>

<td style="text-align:right;">

356

</td>

<td style="text-align:right;">

123

</td>

<td style="text-align:right;">

2.12

</td>

<td style="text-align:right;">

868

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-23

</td>

<td style="text-align:right;">

43

</td>

<td style="text-align:right;">

463

</td>

<td style="text-align:right;">

153

</td>

<td style="text-align:right;">

2.48

</td>

<td style="text-align:right;">

1001

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-24

</td>

<td style="text-align:right;">

46

</td>

<td style="text-align:right;">

535

</td>

<td style="text-align:right;">

146

</td>

<td style="text-align:right;">

2.86

</td>

<td style="text-align:right;">

1301

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-25

</td>

<td style="text-align:right;">

27

</td>

<td style="text-align:right;">

237

</td>

<td style="text-align:right;">

121

</td>

<td style="text-align:right;">

1.44

</td>

<td style="text-align:right;">

1153

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-26

</td>

<td style="text-align:right;">

40

</td>

<td style="text-align:right;">

355

</td>

<td style="text-align:right;">

123

</td>

<td style="text-align:right;">

2.25

</td>

<td style="text-align:right;">

1001

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-27

</td>

<td style="text-align:right;">

33

</td>

<td style="text-align:right;">

380

</td>

<td style="text-align:right;">

149

</td>

<td style="text-align:right;">

2.09

</td>

<td style="text-align:right;">

887

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-28

</td>

<td style="text-align:right;">

33

</td>

<td style="text-align:right;">

401

</td>

<td style="text-align:right;">

147

</td>

<td style="text-align:right;">

2.12

</td>

<td style="text-align:right;">

1070

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-29

</td>

<td style="text-align:right;">

41

</td>

<td style="text-align:right;">

326

</td>

<td style="text-align:right;">

120

</td>

<td style="text-align:right;">

2.10

</td>

<td style="text-align:right;">

798

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-04-30

</td>

<td style="text-align:right;">

80

</td>

<td style="text-align:right;">

790

</td>

<td style="text-align:right;">

145

</td>

<td style="text-align:right;">

3.77

</td>

<td style="text-align:right;">

1334

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-01

</td>

<td style="text-align:right;">

81

</td>

<td style="text-align:right;">

693

</td>

<td style="text-align:right;">

130

</td>

<td style="text-align:right;">

3.86

</td>

<td style="text-align:right;">

1301

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-02

</td>

<td style="text-align:right;">

35

</td>

<td style="text-align:right;">

256

</td>

<td style="text-align:right;">

115

</td>

<td style="text-align:right;">

1.77

</td>

<td style="text-align:right;">

971

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-03

</td>

<td style="text-align:right;">

35

</td>

<td style="text-align:right;">

261

</td>

<td style="text-align:right;">

113

</td>

<td style="text-align:right;">

1.73

</td>

<td style="text-align:right;">

1009

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-04

</td>

<td style="text-align:right;">

41

</td>

<td style="text-align:right;">

351

</td>

<td style="text-align:right;">

120

</td>

<td style="text-align:right;">

2.11

</td>

<td style="text-align:right;">

893

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-05

</td>

<td style="text-align:right;">

69

</td>

<td style="text-align:right;">

738

</td>

<td style="text-align:right;">

150

</td>

<td style="text-align:right;">

3.78

</td>

<td style="text-align:right;">

1330

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-06

</td>

<td style="text-align:right;">

52

</td>

<td style="text-align:right;">

485

</td>

<td style="text-align:right;">

126

</td>

<td style="text-align:right;">

2.83

</td>

<td style="text-align:right;">

1173

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-07

</td>

<td style="text-align:right;">

50

</td>

<td style="text-align:right;">

486

</td>

<td style="text-align:right;">

130

</td>

<td style="text-align:right;">

2.84

</td>

<td style="text-align:right;">

898

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-08

</td>

<td style="text-align:right;">

36

</td>

<td style="text-align:right;">

378

</td>

<td style="text-align:right;">

132

</td>

<td style="text-align:right;">

2.13

</td>

<td style="text-align:right;">

972

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-09

</td>

<td style="text-align:right;">

44

</td>

<td style="text-align:right;">

521

</td>

<td style="text-align:right;">

139

</td>

<td style="text-align:right;">

2.77

</td>

<td style="text-align:right;">

1112

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-10

</td>

<td style="text-align:right;">

39

</td>

<td style="text-align:right;">

360

</td>

<td style="text-align:right;">

124

</td>

<td style="text-align:right;">

2.07

</td>

<td style="text-align:right;">

959

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-11

</td>

<td style="text-align:right;">

87

</td>

<td style="text-align:right;">

735

</td>

<td style="text-align:right;">

113

</td>

<td style="text-align:right;">

3.81

</td>

<td style="text-align:right;">

1356

</td>

</tr>

<tr>

<td style="text-align:left;">

2020-05-12

</td>

<td style="text-align:right;">

42

</td>

<td style="text-align:right;">

511

</td>

<td style="text-align:right;">

137

</td>

<td style="text-align:right;">

2.11

</td>

<td style="text-align:right;">

978

</td>

</tr>

</tbody>

</table>
