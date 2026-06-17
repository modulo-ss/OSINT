First read the report and then examine the pcap files.

And then we look for any valid dns records through each pcap using frame contains "dropbox"

We managed to get a hit in the wiretap-file-06 directory.

https://www.dropbox.com/sh/a4pq1x48zz7fwlw/AACZ9I04AZpXHZF--VDsBQKQa

We then find two files in the dropbox site : invitation, and members list spreadsheet.

Encoded text :

#i'94:d}+(`:+)lXkiu>kj#@+$dd2i'R*(=_kguW+nhS2)N95i=T3:Ume=5=kj5T5(V<kiVN2n&85it82(qn2)#=kj=T5$d_3WdT5)k85)d;3n`N3>48*nuS+>'W+(q;+$d95ed_2i&8&n9=4>h_3np8$iu_+(U82(p8(>h?4>':kiuSkg+W2(#96$U8%(hW*n88|XgQkfkU|;|Qkih_kfgX~;cU{:d&2i&8*nuS+>'W+(q;+$d;+(q_+)k8*)"85i9=kh}@+)l95iuSkg9T5i'Qkiu>+>'W4WdX5ih_+$`T+:`_2i&R*)l_ki+9*n=Q2)#N+)|QkihS+edo+$d:+(VN+)+=ki=_kj5N3iU8*>&85i9=kjd=4>+=*o"84n'_5i=S+Wd>3ok83o'Wki'n+(q_{8@m'i9=ki}T3>+=4>'S*n&85n=Q3edU4>un2(#=kihSkiuU4iuW5j'S2)#qkj#Tki'p*n993>5=ki=<+(hXkihS+edX2ihW+$d:+)}_kjdW*(}_2(}=4Wd93(uS+WdT5)k83('R*>'W4Wp8'n&82ihn+$dQ2(q=+ed`4ed9kj+94>==5j<83n*82n'q3>u_+$dX4i'92n'W4Wd93>"84ihS+(U8+i=X*o'X4n=T3?|85it8+(qX5)l=kj#@*)"85i9=ki}T3>+=4>'S*n&82)|8*>u_2edN3>+T4>`95i=n+$d93>"8+(q?*(5N3>4Se8Nd4WdR+(`:+)lXkiu>kgh@+(`92)"Qkj5=ki9T4i&85i995edq3o&8*nhSkiNT2(p85)|8+>uWkj#@2)|8+)9;2)#N3>48+)+=3?"SkhdQ+(hX+$dR*)lPkj=T5)k8*nhQ+(q<*)lXkihS+edR*(R=kihW4>hS+n'R+(q_4Wd_3Wd95j#=3>"Skh5=kiVT3nQ8+>uW5nhW+ed_3WdX+('N3>486(u`ki=SkhN9+ol=*:gme<=>kj=T5$d@*)+=kihS6$dV5('X5i=T3?|83ok8*nuS*n'W3?|QkjdQ+(hX+$d<3WdS3o"82i'X2)#95i&85it8*nuS5ih;5ed`4Wpme<l=4o"84>'?*)l<4WUme=#@+$df3o'S*n=Q{c@m%np8*>'@*(V>kiu>kj#@+$dd2i'R*(=_kguW+nhS2)N95i=T38yy

We then identify this encoded text through dcode as ROT13  ->  ROT47  ->  Base64

Output :

Dear Members of the Ahemait Organization,

We would like to invite you to our upcoming conference at the Sheraton Hotel in Zagreb on Friday, March 31, 2023, at 13:00. The conference center at the Sheraton Hotel offers state-of-the-art facilities, and we believe it will be the perfect setting for our event.

The conference will provide an opportunity to exchange ideas and share best practices among our members. We have lined up a variety of keynote speakers and panel discussions to ensure that the conference is both informative and engaging.

As members of Ahemait, we hope that you can join us for this exciting event. Please mark your calendars and make arrangements to attend. We look forward to seeing you in Zagreb!

If you have any questions or concerns, please do not hesitate to contact us.

Best regards,

The Council,

On behalf of the Ahemait Organization


hotelname-city-dd-mm-yyyy-hhmm

sheraton-hotel-zagreb-31-03-2023-1300
