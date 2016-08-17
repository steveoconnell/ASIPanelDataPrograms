Files provided on an "as-is" basis.
Originally developed for use in 

How Do Electricity Shortages Affect Industry? Evidence from India
Hunt Allcott, Allan Collard-Wexler and Stephen D. O'Connell

Development done on a Windows 7 PC using Stata 11.

Uses ASI Panel data for years 1998-99 to 2010-11 purchased AFTER August 2013.

Notes at end.

Note that raw data files need to have the following folder structure and names:

[FILE MANIFEST FOLLOWS]

 Directory of \data

01/14/2014  01:50 PM    <DIR>          .
01/14/2014  01:50 PM    <DIR>          ..
11/18/2013  10:53 PM    <DIR>          1998
11/18/2013  10:52 PM    <DIR>          1999
11/18/2013  08:36 PM    <DIR>          2000
11/18/2013  08:36 PM    <DIR>          2001
11/18/2013  08:37 PM    <DIR>          2002
11/18/2013  08:37 PM    <DIR>          2003
11/18/2013  08:38 PM    <DIR>          2004
11/18/2013  08:38 PM    <DIR>          2005
11/18/2013  08:39 PM    <DIR>          2006
11/18/2013  08:35 PM    <DIR>          2007
08/01/2013  12:31 PM    <DIR>          2008
11/18/2013  10:58 PM    <DIR>          2009
02/04/2014  04:08 PM    <DIR>          2010


 Directory of \data\1998

11/18/2013  10:53 PM    <DIR>          .
11/18/2013  10:53 PM    <DIR>          ..
03/16/2012  04:01 AM         1,671,912 OASIBLA98.TXT
03/16/2012  04:02 AM         1,541,531 OASIBLB98.TXT
03/16/2012  04:02 AM        23,790,846 OASIBLC98.TXT
03/16/2012  04:03 AM        15,992,350 OASIBLD98.TXT
03/16/2012  04:04 AM        17,082,742 OASIBLE98.TXT
07/25/2013  06:44 AM         4,743,552 OASIBLF98.TXT
03/16/2012  04:05 AM         3,860,064 OASIBLG98.TXT
03/16/2012  04:05 AM        18,431,182 OASIBLH98.TXT
03/16/2012  04:06 AM           967,890 OASIBLI98.TXT
03/16/2012  04:06 AM        10,381,203 OASIBLJ98.TXT
              10 File(s)     98,463,272 bytes

 Directory of \data\1999

11/18/2013  10:52 PM    <DIR>          .
11/18/2013  10:52 PM    <DIR>          ..
03/16/2012  03:46 AM         2,211,990 OASIBLA99.TXT
03/16/2012  03:47 AM         1,635,715 OASIBLB99.TXT
03/16/2012  03:48 AM        24,836,936 OASIBLC99.TXT
03/16/2012  03:49 AM        16,608,700 OASIBLD99.TXT
03/16/2012  03:50 AM        17,769,620 OASIBLE99.TXT
07/25/2013  06:50 AM         4,925,760 OASIBLF99.TXT
03/16/2012  03:52 AM         3,489,564 OASIBLG99.TXT
03/16/2012  03:52 AM        19,301,051 OASIBLH99.TXT
03/16/2012  03:53 AM           995,764 OASIBLI99.TXT
03/16/2012  03:53 AM        10,560,825 OASIBLJ99.TXT
              10 File(s)    102,335,925 bytes

 Directory of \data\2000

11/18/2013  08:36 PM    <DIR>          .
11/18/2013  08:36 PM    <DIR>          ..
03/16/2012  04:00 AM         2,712,336 OASIBLA1.TXT
03/16/2012  04:01 AM         2,048,929 OASIBLB1.TXT
03/16/2012  04:01 AM        32,026,706 OASIBLC1.TXT
03/16/2012  04:02 AM        21,216,050 OASIBLD1.TXT
03/16/2012  04:03 AM        23,795,644 OASIBLE1.TXT
07/25/2013  07:24 AM         6,225,984 OASIBLF1.TXT
03/16/2012  04:05 AM         4,429,932 OASIBLG1.TXT
03/16/2012  04:05 AM        25,047,715 OASIBLH1.TXT
03/16/2012  04:06 AM         1,349,040 OASIBLI1.TXT
03/16/2012  04:07 AM        13,333,644 OASIBLJ1.TXT
              10 File(s)    132,185,980 bytes

 Directory of \data\2001

11/18/2013  08:36 PM    <DIR>          .
11/18/2013  08:36 PM    <DIR>          ..
03/16/2012  02:31 AM         2,787,972 OASIBLA2.TXT
03/16/2012  02:32 AM         2,194,292 OASIBLB2.TXT
03/16/2012  02:32 AM        35,103,656 OASIBLC2.TXT
03/16/2012  02:33 AM        22,935,750 OASIBLD2.TXT
03/16/2012  02:39 AM        25,738,632 OASIBLE2.TXT
07/25/2013  06:56 AM         6,668,352 OASIBLF2.TXT
03/16/2012  02:42 AM         4,791,384 OASIBLG2.TXT
03/16/2012  02:43 AM        27,056,799 OASIBLH2.TXT
03/16/2012  02:43 AM         1,508,353 OASIBLI2.TXT
03/16/2012  02:45 AM        14,463,702 OASIBLJ2.TXT
              10 File(s)    143,248,892 bytes

 Directory of \data\2002

11/18/2013  08:37 PM    <DIR>          .
11/18/2013  08:37 PM    <DIR>          ..
03/16/2012  02:16 AM         2,761,836 OASIBLA3.TXT
03/16/2012  02:18 AM         2,194,963 OASIBLB3.TXT
03/16/2012  02:19 AM        35,594,654 OASIBLC3.TXT
03/16/2012  02:20 AM        23,148,800 OASIBLD3.TXT
03/16/2012  02:21 AM        26,071,628 OASIBLE3.TXT
07/25/2013  06:59 AM         6,723,072 OASIBLF3.TXT
03/16/2012  02:22 AM         4,834,596 OASIBLG3.TXT
03/16/2012  02:23 AM        27,459,586 OASIBLH3.TXT
03/16/2012  02:23 AM         1,567,335 OASIBLI3.TXT
03/16/2012  02:24 AM        14,630,472 OASIBLJ3.TXT
              10 File(s)    144,986,942 bytes

 Directory of \data\2003

11/18/2013  08:37 PM    <DIR>          .
11/18/2013  08:37 PM    <DIR>          ..
03/16/2012  02:03 AM         3,754,674 OASIBLA4.TXT
03/16/2012  02:04 AM         2,984,669 OASIBLB4.TXT
03/16/2012  02:05 AM        47,557,748 OASIBLC4.TXT
03/16/2012  02:06 AM        30,771,250 OASIBLD4.TXT
03/16/2012  02:07 AM        34,753,360 OASIBLE4.TXT
07/25/2013  07:01 AM         9,069,120 OASIBLF4.TXT
03/16/2012  02:08 AM         6,432,972 OASIBLG4.TXT
03/16/2012  02:09 AM        38,464,272 OASIBLH4.TXT
03/16/2012  02:10 AM         1,931,314 OASIBLI4.TXT
03/16/2012  02:10 AM        19,358,325 OASIBLJ4.TXT
              10 File(s)    195,077,704 bytes

 Directory of \data\2004

11/18/2013  08:38 PM    <DIR>          .
11/18/2013  08:38 PM    <DIR>          ..
03/15/2012  04:06 AM         3,256,440 OASIBLA5.TXT
03/15/2012  04:07 AM         2,705,106 OASIBLB5.TXT
03/15/2012  04:13 AM        41,391,292 OASIBLC5.TXT
03/15/2012  05:08 AM        26,604,650 OASIBLD5.TXT
03/15/2012  05:08 AM        30,436,920 OASIBLE5.TXT
07/25/2013  07:03 AM         7,910,784 OASIBLF5.TXT
03/15/2012  05:09 AM         5,589,168 OASIBLG5.TXT
03/15/2012  05:10 AM        33,462,737 OASIBLH5.TXT
03/15/2012  05:11 AM         1,762,222 OASIBLI5.TXT
03/15/2012  05:12 AM        16,629,723 OASIBLJ5.TXT
              10 File(s)    169,749,042 bytes

 Directory of \data\2005

11/18/2013  08:38 PM    <DIR>          .
11/18/2013  08:38 PM    <DIR>          ..
07/15/2011  06:28 AM         8,710,272 asiblkf6.txt
03/15/2012  03:46 AM         3,782,064 OASIBLA6.TXT
03/15/2012  03:50 AM         2,821,006 OASIBLB6.TXT
03/15/2012  03:51 AM        45,532,436 OASIBLC6.TXT
03/15/2012  03:52 AM        29,058,650 OASIBLD6.TXT
03/15/2012  03:53 AM        33,366,270 OASIBLE6.TXT
07/25/2013  07:05 AM         8,710,272 OASIBLF6.TXT
03/15/2012  03:55 AM         6,645,132 OASIBLG6.TXT
03/15/2012  03:56 AM        36,431,934 OASIBLH6.TXT
03/15/2012  03:56 AM         1,850,464 OASIBLI6.TXT
03/15/2012  03:57 AM        17,893,962 OASIBLJ6.TXT
              11 File(s)    194,802,462 bytes

 Directory of \data\2006

11/18/2013  08:39 PM    <DIR>          .
11/18/2013  08:39 PM    <DIR>          ..
03/15/2012  03:27 AM         4,413,750 OASIBLA7.TXT
03/15/2012  03:31 AM         2,863,706 OASIBLB7.TXT
03/15/2012  03:32 AM        45,615,072 OASIBLC7.TXT
03/15/2012  03:34 AM        29,168,100 OASIBLD7.TXT
03/15/2012  03:35 AM        33,338,186 OASIBLE7.TXT
07/25/2013  07:07 AM         8,626,176 OASIBLF7.TXT
03/15/2012  03:36 AM         6,020,820 OASIBLG7.TXT
03/15/2012  03:37 AM        36,529,570 OASIBLH7.TXT
03/15/2012  03:38 AM         1,894,046 OASIBLI7.TXT
03/15/2012  03:39 AM        17,970,003 OASIBLJ7.TXT
              10 File(s)    186,439,429 bytes

 Directory of \data\2007

11/18/2013  08:35 PM    <DIR>          .
11/18/2013  08:35 PM    <DIR>          ..
03/15/2012  02:59 AM         3,754,608 OASIBLA8.TXT
03/15/2012  03:02 AM         2,430,057 OASIBLB8.TXT
03/15/2012  03:10 AM        40,563,472 OASIBLC8.TXT
03/15/2012  03:11 AM        25,809,500 OASIBLD8.TXT
03/15/2012  03:13 AM        29,264,118 OASIBLE8.TXT
07/25/2013  07:10 AM         7,529,280 OASIBLF8.TXT
03/15/2012  03:15 AM         5,299,632 OASIBLG8.TXT
03/15/2012  03:16 AM        32,341,232 OASIBLH8.TXT
03/15/2012  03:17 AM         1,831,291 OASIBLI8.TXT
03/15/2012  03:18 AM        15,930,666 OASIBLJ8.TXT
              10 File(s)    164,753,856 bytes

 Directory of \data\2008

08/01/2013  12:31 PM    <DIR>          .
08/01/2013  12:31 PM    <DIR>          ..
03/15/2012  11:05 AM         3,750,012 OASIBLA9.TXT
03/15/2012  11:26 AM         2,329,733 OASIBLB9.TXT
03/15/2012  11:29 AM        43,975,350 OASIBLC9.TXT
03/15/2012  11:31 AM        25,534,000 OASIBLD9.TXT
03/15/2012  11:38 AM        35,652,638 OASIBLE9.TXT
03/15/2012  11:40 AM         6,562,080 OASIBLF9.TXT
03/15/2012  11:41 AM         5,776,008 OASIBLG9.TXT
03/15/2012  11:43 AM        31,874,150 OASIBLH9.TXT
03/15/2012  11:44 AM         1,786,708 OASIBLI9.TXT
03/15/2012  11:47 AM        15,430,662 OASIBLJ9.TXT
              10 File(s)    172,671,341 bytes

 Directory of \data\2009

11/18/2013  10:58 PM    <DIR>          .
11/18/2013  10:58 PM    <DIR>          ..
08/01/2013  11:28 AM         3,940,797 OASA10.TXT
08/01/2013  11:29 AM         2,605,735 OASB10.TXT
08/01/2013  11:29 AM        48,005,140 OASC10.TXT
08/01/2013  11:31 AM        27,824,300 OASD10.TXT
08/01/2013  11:32 AM        40,758,428 OASE10.TXT
08/01/2013  11:32 AM         7,217,448 OASF10.TXT
08/01/2013  11:33 AM         6,311,928 OASG10.TXT
08/01/2013  11:34 AM        35,542,640 OASH10.TXT
08/01/2013  11:34 AM         1,862,000 OASI10.TXT
08/01/2013  11:35 AM        18,700,902 OASJ10.TXT
              10 File(s)    192,769,318 bytes

 Directory of \data\2010

02/04/2014  04:08 PM    <DIR>          .
02/04/2014  04:08 PM    <DIR>          ..
08/21/2013  11:07 AM         3,709,253 OASA11.TXT
08/21/2013  11:17 AM         2,409,696 OASB11.TXT
08/21/2013  11:19 AM        56,315,340 OASC11.TXT
08/21/2013  11:20 AM        31,021,218 OASD11.TXT
08/21/2013  11:24 AM        41,597,262 OASE11.TXT
08/21/2013  11:25 AM         8,464,896 OASF11.TXT
08/21/2013  11:27 AM         7,555,008 OASG11.TXT
08/21/2013  11:29 AM        35,433,528 OASH11.TXT
08/21/2013  11:30 AM         1,890,720 OASI11.TXT
08/21/2013  11:31 AM        18,106,416 OASJ11.TXT
08/21/2013  11:44 AM            44,032 Paneldatastruc 2010-11.xls
              11 File(s)    206,547,369 bytes

Be aware of the following corrections that need to be made if you need to use any of these fields:

In 1998 the Block F variable "empTotalDays" is zero for all factories. Only manufacturing days are recorded and one can see in the actual survey that only total days were asked for so I think these figures are incorrectly categorized (empTotalDays should be what empTotalDaysManuf is and empTotalDaysManuf should be missing).

For years 2008-2010 the variables Bonus, Provident and Welfare were not recorded correctly since they were not under the "Total employees (5+6+7+8)" category but under a separate category called "10".
