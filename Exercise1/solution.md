dyn-129-236-213-132:Exercise1 rebeccabartels$ gpg --gen-key
gpg (GnuPG) 2.2.17; Copyright (C) 2019 Free Software Foundation, Inc.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Note: Use "gpg --full-generate-key" for a full featured key generation dialog.

GnuPG needs to construct a user ID to identify your key.

Real name: thathackergirl        
Email address: rebeccafionna@gmail.com
You selected this USER-ID:            
    "thathackergirl <rebeccafionna@gmail.com>"

Change (N)ame, (E)mail, or (O)kay/(Q)uit? O
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
gpg: /Users/rebeccabartels/.gnupg/trustdb.gpg: trustdb created
gpg: key B1B3A6BEE9946668 marked as ultimately trusted
gpg: directory '/Users/rebeccabartels/.gnupg/openpgp-revocs.d' created
gpg: revocation certificate stored as '/Users/rebeccabartels/.gnupg/openpgp-revocs.d/DBAE5BA9E2B8F10A947E6302B1B3A6BEE9946668.rev'
public and secret key created and signed.

pub   rsa2048 2019-10-25 [SC] [expires: 2021-10-24]
      DBAE5BA9E2B8F10A947E6302B1B3A6BEE9946668
uid                      thathackergirl <rebeccafionna@gmail.com>
sub   rsa2048 2019-10-25 [E] [expires: 2021-10-24]

dyn-129-236-213-132:Exercise1 rebeccabartels$ ls
readme.md
dyn-129-236-213-132:Exercise1 rebeccabartels$ gpg --list-key
gpg: checking the trustdb
gpg: marginals needed: 3  completes needed: 1  trust model: pgp
gpg: depth: 0  valid:   1  signed:   0  trust: 0-, 0q, 0n, 0m, 0f, 1u
gpg: next trustdb check due at 2021-10-24
/Users/rebeccabartels/.gnupg/pubring.kbx
----------------------------------------
pub   rsa2048 2019-10-25 [SC] [expires: 2021-10-24]
      DBAE5BA9E2B8F10A947E6302B1B3A6BEE9946668
uid           [ultimate] thathackergirl <rebeccafionna@gmail.com>
sub   rsa2048 2019-10-25 [E] [expires: 2021-10-24]

dyn-129-236-213-132:Exercise1 rebeccabartels$ gpg --list-keys
/Users/rebeccabartels/.gnupg/pubring.kbx
----------------------------------------
pub   rsa2048 2019-10-25 [SC] [expires: 2021-10-24]
      DBAE5BA9E2B8F10A947E6302B1B3A6BEE9946668
uid           [ultimate] thathackergirl <rebeccafionna@gmail.com>
sub   rsa2048 2019-10-25 [E] [expires: 2021-10-24]

dyn-129-236-213-132:Exercise1 rebeccabartels$ gpg -output dzkey.gpg --export rebeccafionna@gmail.com
gpg: Note: '--export' is not considered an option
gpg: WARNING: no command supplied.  Trying to guess what you mean ...
usage: gpg [options] [filename]
dyn-129-236-213-132:Exercise1 rebeccabartels$ ls
readme.md
dyn-129-236-213-132:Exercise1 rebeccabartels$ gpg --output dzkey.gpg --export rebeccafionna@gmail.com
dyn-129-236-213-132:Exercise1 rebeccabartels$ ls
dzkey.gpg	readme.md
dyn-129-236-213-132:Exercise1 rebeccabartels$ cat dzkey.gpg 
]?U???? ??+9?i?Fn+LmO?j?W|?@^?ﰓ?n?e
                                   ??וZz?`P??X就f?z?}?&?3???]y~%vz
?????Oة/IP D?H?Ip???;?}???UghV=?L?ѳ???Ẹ?j                         _?
                                         ?EQ?"?????????ֽ[??
??????????wu?Υ<?G??F????h
                         b ?????O???
-V?z???)
        ?|??.@?\???:t~?6k?? z??*7?a?B+,?m??*H&B?-?(thathackergirl <rebeccafionna@gmail.com>?>!ۮ[???
?~c?????fh]?U?	?g
                  	
	
       ?
	?????fh??'?$r,??Vh????/,?|??տL?L?G?b?+?L?????:??2?????1e????EI?塀?\$??t"??d
                                                                                   O?ɓg??Ihҹ	??@?8N?e?VR?HnN5?6$6V??rp?{??K???QQx?Q?aG?i?7`???A??V
                                                                                                                                                     ?Y^g?[?ڕԛ???pDٕq?Srk??c???"o?F?[vh????[`?Y??G?[eD????Ӣ??????????'@fQ<?C????-???۱?
\???$??;?5(?~?g?uMᴗ1.8?M?R?ş
                            ??,h
???z??x۰M??յ?"J?V?X?G?Y^^>$?ِ?_i5??-%-?0?×R?s?μ?????$
?1T???n?f
|?0??))?8э\??R???D???r????`???YAr-?_???2Z?/o?&!ۮ[???
?~c?????fh]?U?
              	?g
?ub?{?L?B??t?Re?ڢ??@ОlN`?ͮ???Ef??B?C0?cԱT$?-?I?P?!7?Qe))?-?Rc;?%?0????11???7[B"?B?T??y?b??sY
                                                                                           ???'(!ОO0?w?Gh??W??l???7S`??:??l?.?{y
m?i??yP%?I????9??~SG??g?#???̳?O?B???/]?,?k?R>dyn-129-236-213-132:Exercise1 rebeccabartels$ 
