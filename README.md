# Protobi NHANES Data Repository
This repository contains survey data and metadata for the [CDC National Health and Nutrition Evaluation Survey (NHANES)](https://www.cdc.gov/nchs/nhanes/index.html).

This builds on the download of XPT and HTM files by https://www.reddit.com/user/Ancient_Winter/ and archived at https://archive.org/details/continuous-nhanes
It also contains translations of the SAS Transport .xpt data files to text `.csv` and SPSS `.sav` datafiles.

Submit corrections and requests for this repository via the "Issues" and "Pull requests" links above.

## Installation
Use Git to clone this repository.  You may need to download git command line or GitHub Desktop.  This will download all the files to your local machine
in a way that makes it easier to receive and contribute updates over time.

You can also download individual files via the links above within this GitHub index page.

From the command line enter:
`git clone https://github.com/protobi/protobi-data-nhanes`


## Structure

This currently contains data for all data tables from the NHANES Continuous Survey, beginning with the first year it was fielded, data year 1999-2000.

Modules:
* Demographics
* Questionnaire
* Dietary
* Examination
* Laboratory


Suffix | Year
--|------------
L | 2021-2023
P | 2017-2020
I | 2015-2016
H | 2013-2014
G | 2011-2012
F | 2009-2010
E | 2007-2008
D | 2005-2006
C | 2003-2004
B | 2001-2002
A | 1999-2000

## Data tables in latest NHANES release

The latest release 2021-2023 includes the following tables in these modules:

|Demographics | Dietary	| Examination	| Laboratory	| Questionnaire
|----|----|----|----|----
|DEMO_L	|DR1IFF_L	|BAX_L	|AGP_L	|ACQ_L
|	|DR1TOT_L	|BMX_L	|CBC_L	|ALQ_L
|	|DR2IFF_L	|BPXO_L	|FASTQX_L	|AUQ_L
|	|DR2TOT_L	|LUX_L	|FERTIN_L	|BAQ_L
|	|DRXFCD_L	|	|FOLATE_L	|BPQ_L
|	|	|	|FOLFMS_L	|DBQ_L
|	|	|	|GHB_L	|DEQ_L
|	|	|	|GLU_L	|DIQ_L
|	|	|	|HDL_L	|DPQ_L
|	|	|	|HEPA_L	|ECQ_L
|	|	|	|HEPB_S_L	|FNQ_L
|	|	|	|HSCRP_L	|HEQ_L
|	|	|	|IHGEM_L	|HIQ_L
|	|	|	|INS_L	|HOQ_L
|	|	|	|PBCD_L	|HSQ_L
|	|	|	|TCHOL_L	|HUQ_L
|	|	|	|TFR_L	|IMQ_L
|	|	|	|TST_L	|INQ_L
|	|	|	|UCPREG_L	|KIQ_U_L
|	|	|	|VID_L	|MCQ_L
|	|	|	|	|OCQ_L
|	|	|	|	|OHQ_L
|	|	|	|	|PAQY_L
|	|	|	|	|PAQ_L
|	|	|	|	|PUQMEC_L
|	|	|	|	|RHQ_L
|	|	|	|	|RXQASA_L
|	|	|	|	|RXQ_RX_L
|	|	|	|	|SLQ_L
|	|	|	|	|SMQFAM_L
|	|	|	|	|SMQRTU_L
|	|	|	|	|SMQ_L
|	|	|	|	|WHQ_L

## Data tables by release
### Unique by seqn
TABLE | CYCLE
-- | --
ACQ | A,B,C,D,E,F,G,H,I,L,P
AGP | L
ALQ | A,B,C,D,E,F,G,H,I,L,P
AUQ | A,B,C,D,E,F,G,I,L,P
BAQ | A,B,C,L
BAX | A,B,C,L
BMX | A,B,C,D,E,F,G,H,I,L,P
BPQ | A,B,C,D,E,F,G,H,I,L,P
BPXO | L,P
CBC | D,E,F,G,H,I,L,P
DBQ | A,B,C,D,E,F,G,H,I,L,P
DEMO | A,B,C,D,E,F,G,H,I,L,P
DEQ | A,B,C,D,F,G,H,I,L,P
DIQ | A,B,C,D,E,F,G,H,I,L,P
DPQ | D,E,F,G,H,I,L,P
DR1TOT | C,D,E,F,G,H,I,L,P
DR2TOT | C,D,E,F,G,H,I,L
ECQ | A,B,C,D,E,F,G,H,I,L,P
FASTQX | D,E,F,G,H,I,P,L
FERTIN | D,E,F,I,L,P
FNQ | L
FOLATE | D,E,F,G,H,I,P,L
FOLFMS | E,G,H,I,L,P
GHB | D,E,F,G,H,I,P,L
GLU | D,E,F,G,H,I,L,P
HDL | D,E,F,G,H,I,P,L
HEPA | D,E,F,G,H,I,P,L
HEPB_S | D,E,F,G,H,I,P,L
HEQ | H,I,L,P
HIQ | A,B,C,D,E,F,G,H,I,L,P
HOQ | A,B,C,D,E,F,G,H,I,L
HSCRP | I,P,L
HSQ | A,B,C,D,E,F,G,H,I,L,P
HUQ | A,B,C,D,E,F,G,H,I,L,P
IHGEM | G,H,I,L,P
IMQ | A,B,C,D,E,F,G,H,I,L,P
INQ | E,F,G,H,I,L,P
INS | H,I,P,L
KIQ_U | B,C,D,E,F,G,H,I,L,P
LUX | P,L
MCQ | A,B,C,D,E,F,G,H,I,L,P
OCQ | A,B,C,D,E,F,G,H,I,P,L
OHQ | A,B,C,D,E,F,G,H,I,P,L
PAQ | A,B,C,D,E,F,G,H,I,P,L
PAQY | P,L
PBCD | D,E,F,G,H,I,L,P
PUQMEC | D,E,F,G,H,I,P,L
RHQ | A,B,C,D,E,F,G,H,I,P,L
RXQASA | G,H,I,P,L
RXQ_RX | L
SLQ | D,E,F,G,H,I,P,L
SMQ | A,B,C,D,E,F,G,H,I,P,L
SMQFAM | A,B,C,D,E,F,G,H,I,P,L
SMQRTU | D,E,F,G,H,I,P,L
TCHOL | D,E,F,G,H,I,P,L
TFR | D,E,F,I,P,L
TST | G,H,I,L,P
UCPREG | D,E,F,G,H,I,P,L
VID | G,H,I,L
WHQ | A,B,C,D,E,F,G,H,I,P,L

### Not unique by seqn
TABLE | CYCLES
-- | --
AUXWBR | I,P
DR1IFF | C,D,E,F,G,H,I,L
DR2IFF | C,D,E,F,G,H,I,L
DRXIFF | A,B
DS1IDS | E,F,G,H,I
DS2IDS | E,F,G,H,I
DSQ2 | B,C,D
DSQFILE2 | A
DSQIDS | E,F,G,H,I
FFQDC | C,D
PAQIAF | A,B,C,D
PAXDAY | H
RXQANA | B,C
RXQ_RX | B,C,D,E,F,G,H,I,P
SSHPV | F
 

### Not indexed by seqn
TABLE | CYCLES
-- | --
BFRPOL | D,E,F,G,H,I
DOXPOL | D,E,F,G,I
DRXFCD | C,D,E,F,G,H,I,L
DRXFMT | A,B
DRXMCD | C,D,E,F,G
DSBI | A
DSII | A
DSPI | A
FOODLK | C,D
PCBPOL | D,E,F,G,H,I
PSTPOL | D,E,F,G,H,I
SSANA2 | A,G
SSBFR | B
SSPCB | B
SSPST | B
VARLK | C,D
