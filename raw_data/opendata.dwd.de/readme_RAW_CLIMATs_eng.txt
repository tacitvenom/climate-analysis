Description of data set, referring to the ASCII code of the CLIMAT reports, FM 71

Parameters of section 1 of the CLIMAT report: 
year;month;IIiii;G1;Po;G1;P;G1;sn;T;st;G1;sn;Tx;sn;Tn;G1;e;G1;R1;Rd;nr;
G1;S1;ps;G1;mp;mT;mTx;mTn;G1;me;mR;mS

sn  = Sign of the data, coded
0 Positive or zero (for temperature)
1 Negative (for temperature)
9 Indicator that relative humidity follows 

year
 
month = Month of the year 

IIiii = WMO Station number


G1 = group index of section 1 of the CLIMAT report

Po = Monthly mean pressure at station level, in tenths of a hectopascal 

P   = Monthly mean sea level pressure, in tenths of a hectopascal, 
      or for stations in mountainous regions monthly mean geopotential, in standard geopotential metres 

sn  = Sign of the data, and relative humidity indicator

T   = Monthly mean air temperature, in tenths of a degree Celsius, its sign being given by sn

st  = Standard deviation of daily mean temperatures of the month, in tenths of a degree Celsius

Tx  = Mean daily maximum air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

Tn  = Mean daily minimum air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

e   = Mean vapour pressure for the month, in tenths of a hectopascal

R1  = Total precipitation for the month in millimetres

Rd  = Frequency group (quintile) within R1 falls

nr  = Number of days in the month with precipitation equal to or greater than 1 millimetreS1  = Total sunshine for the month in hours

ps  = Percentage of total sunshine duration relative to the normal

mP  = Number of days missing from the records for pressure

mT  = Number of days missing from the records for air temperature

mTx = Number of days missing from the record for daily maximum air temperature

mTn = Number of days missing from the record for daily minimum air temperature

me  = Number of days missing from the records for vapour pressure

mR  = Number of days missing from the records for precipitation

mS  = Number of days missing from the records for sunshine duration


Parameters of section 2 of the CLIMAT report (long-term averages): 
G2;Yb;Yc;G2;Po;G2;P;G2;sn;T;st;G2;sn;Tx;sn;Tn;G2;e;G2;R1;nr;G2;S1;G2;YP;YT;YTx;G2;Ye;YR;YS;

G2  = group index of section 2

Yb  = Year of beginning of the reference period

Yc  = Year of ending of the reference period

Po  = Monthly mean pressure at station level, in tenths of a hectopascal

P   = Monthly mean pressure, in tenths of a hectopascal
      or for stations in mountainous regions monthly mean geopotential, in standard geopotential metres

sn  = Sign of the data, and relative humidity indicator

T   = Monthly mean air temperature, in tenths of a degree Celsius, its sign being given by sn

st  = Standard deviation of daily mean values relative to the monthly mean air temperature, in
      tenths of a degree Celsius

Tx  = Mean daily maximum air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

Tn  = Mean daily minimum air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

e   = Mean vapour pressure for the month, in tenths of a hectopascal

R1  = Total precipitation for the month in millimetres

nr  = Number of days in the month with precipitation equal to or greater than 1 millimetre

S1  = Total sunshine for the month in hours

yP  = Number of missing years within the reference period from the calculation of pressure normal

yR  = Number of missing years within the reference period from the calculation of normal for
      precipitation

yS  = Number of missing years within the reference period from the calculation of normal for
      sunshine duration

yT  = Number of missing years within the reference period from the calculation of normal for
      mean air temperature

yTx = Number of missing years within the reference period from the calculation of normal for
      mean extreme air temperature

ye  = Number of missing years within the reference period from the calculation of vapour
      pressure normal


Parameters of section 3 of the CLIMAT report: 
G3;T25;T30;G3;T35;T40;G3;Tn0;Tx0;G3; R01;R05;G3;R10;R50;G3;R100;R150;G3;s00;s01;
G3;s10;s50;G3;f10;f20;f30;G3;V1;V2;V3;

G3   = group index of section 3

T25  = Number of days in the month with maximum air temperature equal to or more than 25�C

T30  = Number of days in the month with maximum air temperature equal to or more than 30�C

T35  = Number of days in the month with maximum air temperature equal to or more than 35�C

T40  = Number of days in the month with maximum air temperature equal to or more than 40�C

Tn0  = Number of days in the month with minimum air temperature less than 0�C

Tx0  = Number of days in the month with maximum air temperature less than 0�C

R01  = Number of days in the month with precipitation equal to or more than 1.0 mm

R05  = Number of days in the month with precipitation equal to or more than 5.0 mm

R10  = Number of days in the month with precipitation equal to or more than 10.0 mm

R50  = Number of days in the month with precipitation equal to or more than 50.0 mm

R100 = Number of days in the month with precipitation equal to or more than 100.0 mm

R150 = Number of days in the month with precipitation equal to or more than 150.0 mm

s00  = Number of days in the month with snow depth more than 0 cm

s01  = Number of days in the month with snow depth more than 1 cm

s10  = Number of days in the month with snow depth more than 10 cm

s50  = Number of days in the month with snow depth more than 50 cm

f10  = Number of days in the month with observed or recorded wind speed equal to or more than
       10 metres per second or 20 knots

f20  = Number of days in the month with observed or recorded wind speed equal to or more than
       20 metres per second or 40 knots

f30  = Number of days in the month with observed or recorded wind speed equal to or more than
       30 metres per second or 60 knots

V1   = Number of days in the month with observed or recorded visibility less than 50 m, irrespective
       of the duration of the observational period

V2   = Number of days in the month with observed or recorded visibility less than 100 m, irrespective
       of the duration of the observational period

V3   = Number of days in the month with observed or recorded visibility less than 1 000 m, irrespective
       of the duration of the observational period

Parameters of section 4 of the CLIMAT report: 
G4;sn;Txd;yx;G4;sn;Tnd;yn;G4;sn;Tax;yax;G4;sn;Tan;yan;G4;Rx;yr;G4;iw;fx;yfx;G4;Dts;Dgr;G4;iy;Gx;Gn

G4  = group index of section 4

sn  = sign of the data, and relative humidity indicator

Txd = Highest daily mean air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

yx  = Day of highest daily mean air temperature during the month

Tnd = Lowest daily mean air temperature of the month, in tenths of a degree Celsius, its sign
      being given by sn

yn  = Day of lowest daily mean air temperature during the month

Tax = Highest air temperature of the month, in tenths of a degree Celsius, its sign being given by sn

yax = Day of highest air temperature during the month

Tan = Lowest air temperature of the month, in tenths of a degree Celsius, its sign being given by sn

yan = Day of lowest air temperature during the month

Rx  = Highest daily amount of precipitation during the month, in tenths of a millimetre

yr  = Day of highest daily amount of precipitation during the month

iw  = Indicator for source and units of wind speed

fx  = Highest gust wind speed observed or recorded during the month, in tenths of units
      indicated by iw

yfx = Day of highest observed or recorded wind speed during the month

Dts = Number of days in the month with thunderstorm(s).

Dgr = Number of days in the month with hail.

iy  = Indicator to specify type of reading of extreme temperatures (only to report in the case of changes)

Gn  = Principal time of daily reading in UTC (hours) of minimum extreme temperature

Gx  = Principal time of daily reading in UTC (hours) of maximum extreme temperature