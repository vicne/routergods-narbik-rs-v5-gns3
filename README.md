RouterGods
Micronics Training (Narbik) Workbook GNS3 Workbook conversion

----------------------------------------

Foundation Volume 1 (Feb 2015) - Completed, tested
Foundation Volume 2 (Feb 2015) - Completed, tested
Advanced Routing and Switching Volume 1 (Feb 2015) - Completed, tested
Advanced Routing and Switching Volume 2 (Feb 2015) - Completed, tested
Advanced Routing and Switching Volume 3 (Mar 2015) - Completed
Advanced Routing and Switching Volume 4 (Feb 2015) - Mostly complete

------------------------------------
Change Log

March 29, 2016
ADV RS Vol 2 - Updated MPLS Lab 10, missing serial link between R1 and R3

Jan 17, 2016
ADV RS Vol 1-3 updated for GNS3 1.4 and 7200 M9 IOS.. QOS section still needs population

Jan 15, 2016
All foundation labs updated for GNS3 1.4 and 7200 M9 IOS

Jan 13, 2016
foundation vol 2 - ip services updated


Nov 29, 2015

Updated DMVPN labs to 7200 M9 

Sept 12, 2015

MPLS Lab 1, ospf config fixed.. lo1 were accidentally added, r3 lo0 was missing

Sept 12, 2015

Lots of minor fixes
Updated ipv6 advanced labs

August 21, 2015

The 15.2-4(M8) seems unstable in multicast labs, so continue using the S series for all the labs EXCEPT for DMVPN Redirect related ones.
Minor fixes to DMVPN labs
Moar fixes to MPLS and BGP Advanced Workbook labs

August 18, 2015

Fixed some DMVPN labs to use 15.2-4(M8) image.  The ip nhrp redirect command doesn't work in the S series.

August 10, 2015

Foundation DMVPN IP fix
Adv Security Workbook, several labs added

August 5, 2015

DMVPN labs converted to 7200 - note the original ips of 192.1.X.X has changed to 192.1.1.X
Adv Multicast touchup fixes.  
Adv OSPF labs 1-6 converted to 7200 router
Adv OSPF Lab 2 needs some more work to be completed, but you can do about 70% of the tasks

TODO - There are still a few labs that need to be converted from the 3725 to 7200 routers

August 3, 2015

Adv Multicast Lab 5, fixes to R2 and R5 configs.  They were missing some commands.

August 2, 2015

Fixes and improvements to Adv Multicast.  Some topos were missing ip addresses.  Every multicast lab now has an option for completed igp and sparse or sparse-dense mode (depending on the lab)  Amazingly all multicast labs seem to work well (unlike 2-3 years ago when GNS3 would bomb out with Multicast)

When pinging multicast addresses, use repeat 1 !!!!

July 31, 2015

Minor fixes to Adv Workbook MPLS.  Finished Labs 1-10 Multicast

July 29, 2015
Massive improvements to Adv Workbook BGP and MPLS.  Every MPLS lab now has an "ospfconfigured" option that will save you time if you have no need to torture yourself with OSPF.

July 21, 2015
Lots of corrections, mostly to Advanced Workbook 1 and 4

July 14, 2015
IPs added to Redist Foundation Lab 1

July 4, 2015

Foundation BGP updated

June 30, 2015

Lots of fixes

June 17, 2015

Several fixes to Foundation OSPF Labs

June 3, 2015

DMVPN files updated to include basic ip addressing
Minor fixes and no cdp log duplex mismatch added

April 16, 2015 *** This is a best effort project and I have not fully validated the workbook against these configs, however, I believe this conversion should work for most of the workbook. ****

Notes

1.  Most of Foundation doesn't have initial configs because Narbik wants you to type everything... however, for certain labs we've added an option to have all ips configured

2.  Interface numbers may be different than the workbook (especially on the large labs).... adjust your configuration/verification accordingly.

3.  Images used

Please use the c7200-adventerprisek9-mz.152-4.M9 image

4.  GNS3 version used = 1.4.0, but should be ok on future versions

