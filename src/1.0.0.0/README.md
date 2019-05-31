# GALILEO Local Data Dictionary

The galileo dictionary contains classes that describe aspects of a fictious mission and related instruments.

Version: 1.0.0.0  
Steward: ppi

## Classes

### Inst
The Galileo class is the container for Galileo specific metadata elements.

Attribute    | Min Occur. | Max Occur.  
------------ | ---------- | ----------- 
[inst.brightness](#inst.brightness) | 0 | 1
[inst.max_exposure](#inst.max_exposure) | 0 | 1

### GALILEO
The GALILEO class is the container for mission-specific metadata elements.

Attribute    | Min Occur. | Max Occur.  
------------ | ---------- | ----------- 
[mission_phase_name](#mission_phase_name) | 0 | 1
[spacecraft_clock_start_count](#spacecraft_clock_start_count) | 0 | 1
[spacecraft_clock_stop_count](#spacecraft_clock_stop_count) | 0 | 1
[inst](#inst) | 0 | 1
## Attributes


### mission_phase_name
The mission_phase_name attribute provides the mission-defined name of a mission phase.

Type: ASCII_Short_String_Collapsed  
Units: undefined  

**Permissible Values**

Name                                    | Description
--------------------------------------- | ----------------------------
Launch | 1989-10-17 (1989-290)to 1989-10-17 (1989-299)
Interplanetary Cruise | 1989-10-17 (1989-290) to 1989-10-26 (1989-299)
Earth Venus Cruise | 1989-10-26 (1989-299) to 1995-10-09 (1995-282)
4-Day Checkout | 1989-10-26 (1989-299) to 1990-02-19 (1990-50)
Venus Encounter | 1989-12-27 (1989-361) to 1989-12-31 (1989-365)
Venus Earth Cruise | 1990-02-07 (1990-38) to 1990-02-19 (1990-50)
Earth1 Encounter | 1990-02-19 (1990-50) to 1991-04-21 (1991-119)
Earth-Earth Cruise | 1990-11-08 (1990-312) to 1990-12-16 (1990-350)
GASPRA Encounter | 1991-04-29 (1990-119) to 1993-04-12 (1993-102)
Earth Jupiter Cruise | 1990-02-19 (1990-50) to 1991-04-21 (1991-111)
IDA Encounter | 1993-04-12 (1993-102) to 1995-10-09 (1995-282)
Probe Release and ODM | 1994-07-16 (1994-197) to 1994-07-22 (1994-203)
Jupiter Orbit Operations | 1995-07-05 (1995-186) to 1995-07-31 (1995-221)
Prime Mission Orbit Operations | 1994-07-16 (1994-197) to 1994-07-22 (1994-203)
Jupiter Approach | 1995-10-09 (1995-282) to 1997-12-15 (1994-349)
Jupiter 0 Orbit | 1995-10-09 (1995-282) to 1995-12-03 (1995-337)
Jupiter 0 Orbit | 1995-10-09 (1995-282) to 1995-12-03 (1995-337)
IO 0 Encounter | 1995-12-03 (1995-337) to 1996-06-23 (1996-175)
Probe | 1995-12-03 (1995-337) to 1996-01-03 (1996-3)
Ganymede 1 Orbit | 1995-12-07 (1995-341) to 1995-12-07 (1995-341)
Ganymede 1 Encounter | 1996-06-23 (1996-175) to 1996-09-01 (1996-245)
Ganymede 2 Orbit | 1996-06-23 (1996-175) to 1996-06-30 (1996-182)
Ganymede 2 Encounter | 1996-09-01 (1996-245) to 1996-11-02 (1996-302)
Callisto 3 Orbit | 1996-09-01 (1996-245) to 1996-09-08 (1995-252)
Callisto 3 Encounter | 1996-11-02 (1996-307) to 1996-12-15 (1996-350)
Europa 4 Orbit | 1996-11-02 (1996-307) to 1996-11-11 (1996-316)
Europa 4 Encounter | 1996-12-15 (1996-350) to 1997-02-16 (1997-47)
Europa 6 Orbit | 1996-12-15 (1996-350) to 1996-12-22 (1996-357)
Europa 6 Encounter | 1997-02-16 (1996-47) to 1997-03-30 (1997-89)
Ganymede 7 Orbit | 1997-02-16 (1996-47) to 1997-02-23 (1997-54)
Ganymede 7 Encounter | 1997-03-30 (1997-89) to 1997-05-04 (1997-124)
Ganymede 8 Orbit | 1997-03-30 (1997-89) to 1997-04-06 (1997-96)
Ganymede 8 Encounter | 1997-05-04 (1997-124) to 1997-06-22 (1997-173)
Callisto 9 Orbit | 1997-05-04 (1997-124) to 1997-05-11 (1997-131)
Callisto 10 Orbit | 1997-06-22 (1997-173) to 1997-06-29 (1997-180)
Callisto 10 Encounter | 1997-09-14 (1997-173) to 1997-11-14 (1997-318)
Europa 11 Orbit | 1997-09-14 (1997-257) to 1997-09-20 (1997-263)
Europa 11 Encounter | 1997-11-02 (1997-306) to 1997-12-15 (1997-349)
Europa Campaign | 1997-11-02 (1997-306) to 1997-11-09 (1997-313)
Orbiter Europa 12 Orbit | 1997-12-15 (1997-349) to 1999-05-02 (1999-122)
Europa 12 Encounter | 1997-12-15 (1997-349) to 1998-02-09 (1998-40)
Europa 13 Orbit | 1997-12-15 (1997-349) to 1997-12-17 (1997-351)
Europa 14 Orbit | 1998-02-09 (1998-40) to 1998-03-28 (1997-87)
Europa 14 Encounter | 1998-03-28 (1998-87) to 1998-05-30 (1998-150)
Europa 15 Orbit | 1998-03-28 (1998-87) to 1998-03-31 (1998-90)
Europa 15 Encounter | 1998-05-30 (1998-150) to 1998-07-20 (1998-201)
Europa 16 Orbit | 1998-05-30 (1998-150) to 1998-06-30 (1998-181)
Europa 16 Encounter | 1998-07-20 (1998-201) to 1998-09-25 (1998-268)
Europa 17 Orbit | 1998-07-20 (1998-201) to 1998-07-29 (1998-210)
Europa 17 Encounter | 1998-09-25 (1998-268) to 1998-11-21 (1998-316)
Europa 18 Orbit | 1998-09-25 (1998-268) to 1998-09-28 (1998-271)
Europa 18 Encounter | 1998-11-21 (1998-325) to 1999-01-31 (1999-31)
Europa 19 Orbit | 1998-11-21 (1998-325) to 1999-11-24 (1999-328)
Europa 19 Encounter | 1999-01-31 (1999-349) to 1999-05-02 (1997-351)
Perijove Reduction Campaign | 1999-01-31 (1999-31) to 1999-02-11 (1999-42)
Orbiter Callisto 20 Orbiter | 1999-05-02 (1999-122) to 1999-10-10 (1999-283)
Callisto 20 Encounter | 1999-05-02 (1999-122) to 1999-06-29 (1999-180)
Callisto 21 Orbit | 1999-05-02 (1999-122) to 1999-05-07 (1999-127)
Callisto 21 Encounter | 1999-06-29 (1999-180) to 1999-08-11 (1999-223)
Callisto 22 Orbit | 1999-06-29 (1999-180) to 1999-07-03 (1999-184)
Callisto 22 Encounter | 1999-08-11 (1999-223) to 1999-09-13 (1999-256)
Callisto 23 Orbit | 1999-08-11 (1999-223) to 1999-08-14 (1999-226)
Callisto 23 Encounter | 1999-09-13 (1999-256) to 1999-10-10 (1999-283)
IO Campaign | 1999-09-13 (1999-256) to 1999-09-17 (1999-260)
Orbiter IO 24 Orbit | 1999-10-10 (1999-283) to 2000-05-20 (2000-141)
IO 24 Encounter | 1999-10-10 (1999-283) to 1999-11-25 (1999-330)
IO 25 Orbit | 1999-10-10 (1999-283) to 1999-10-14 (1999-287)
IO 25 Encounter | 1999-11-25 (1999-330) to 2000-01-02 (2000-2)
Europa 26 Orbit | 1999-11-25 (1999-330) to 1999-11-27 (1999-331)
Europa 26 Encounter | 2000-01-02 (2000-2) to 2000-02-20 (2000-51)
IO 27 Orbit | 2000-01-01 (2000-1) to 2000-01-05 (2000-5)
IO 27 Encounter | 2000-02-20 (2000-51) to 2000-05-17 (2000-138)
Galileo-Cassini Phase | 2000-02-20 (2000-51) to 2000-02-25 (2000-56)
Galileo-Cassini Phase | 2000-02-20 (2000-51) to 2000-02-25 (2000-56)
Orbiter Ganymede 28 Orbit | 2000-05-17 (2000-51) to 2001-02-05 (2001-36)
Ganymede 28 Encounter | 2000-05-20 (2000-141) to 2000-12-27 (2000-362)
Ganymede 29 Orbit | 2000-05-17 (2000-138) to 2000-06-13 (2000-165)
Ganymede 29 Encounter | 2000-12-27 (2000-362) to 2001-05-22 (2001-142)
IO Campaign | 2000-12-26 (2000-361) to 2001-02-05 (2001-36)
Orbiter Callisto 30 Orbit | 2001-05-22 (2001-142) to 2002-01-20 (2002-20)
Callisto 30 Encounter | 2001-05-22 (2001-361) to 2001-08-04 (2002-216)
IO 31 Orbit | 2001-05-22 (2001-361) to 2001-05-27 (2001-147)
IO 31 Encounter | 2001-08-04 (2001-216) to 2001-10-14 (2001-287)
IO 32 Orbit | 2001-08-04 (2001-216) to 2001-08-09 (2001-221)
IO 32 Encounter | 2001-10-14 (2001-287) to 2002-01-15 (2002-15)
IO 33 Orbit | 2001-10-14 (2001-287) to 2001-10-29 (2001-302)
IO 33 Encounter | 2002-01-15 (2002-15) to 2002-11-02 (2002-306)
Inner Jupiter Phase | 2002-01-15 (2002-15) to 2002-01-20 (2002-20)
Orbiter Amalthea 34 Orbit | 2002-11-02 (2002-306) to 2003-09-21 (2003-264)
Amalthea 34 Encounter | 2002-11-02 (2002-306) to 2003-09-21 (2003-264)
Jupiter 35 Orbit | 2002-11-02 (2002-306) to 2002-11-08 (2003-312)


### spacecraft_clock_start_count
The spacecraft_clock_start_count attribute provides the value 
		of the spacecraft clock at the beginning of a time period of 
		interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  



### spacecraft_clock_stop_count
The spacecraft_clock_stop_count attribute provides the value of the spacecraft 
		clock at the beginning of a time period of interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  



### brightness
The background brightness used for 
					 automatic exposure time calculation.

Type: ASCII_Integer  
Units: undefined  
Maximum Value: 4095  



### max_exposure
The maximum allowable exposure time 
					 from an automatic exposure time 
					 calculation.

Type: ASCII_Integer  
Units: undefined  
Maximum Value: 989  


