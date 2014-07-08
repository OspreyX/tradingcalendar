# Trading Calendar #

__This project is not yet functional, this statement will be removed when the code
is in a working state.__

tradingcalendar is a library that creates a pandas DatetimeIndex with market full
and half calendar holidays.

The modules within started in the Zilpline project,
https://github.com/quantopian/zipline and were removed by filtering the files
that were not directly related with the trading calendar, so that correct
attribution is retained.

This project may end up being a stand-alone project, and useable in a similar as
pytz is used for time zones.
But the maintainers are amenable to upstreaming the logic into pandas.
(See, https://github.com/pydata/pandas/issues/7070)

If the rrulles logic is upstreamed to pandas, there will probably be need to get
copyright signoff from the non-Quantopian contributors.
The main NYSE/US Equity calendar is wholly commits from Quantopian employees,
so that set of copyrights can be more quickly assigned.

Contact: opensource@quantopian.com
