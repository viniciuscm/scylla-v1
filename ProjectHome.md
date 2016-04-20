## As seen at DEF CON 20 ##

When there's no technical vulnerability to exploit, you should try to hack what humans left for you, and believe me, this always works.

Scylla provides all the power of what a real audit, intrusion, exclusion and analysis tool needs, giving the possibility of scanning dynamically miss configuration bugs.
Scylla try to be a better tool for security auditors, extremely faster, designed based on real scenarios, developed by experienced coders and constructed with the actual IT work methods.
The words “Configuration Tracer” are the best definition for Scylla, a tool to help on IT audits.

Forget about GNU GPL or any other licence, Scylla licence is: Get what you need, do what you need, but don't be an asshole, don't sell what's mine, tell people that i did it (unless you copy a couple of lines :P) and then do what ever you want, just don't be a jerk.

http://code.google.com/p/scylla-v1/wiki/ScyllaScreenShots -> screenshots!

Here you'll find stuff from (some times guides, some times just a c+p from their source or an app):

**Nmap (www.nmap.org - fyodor):**  ncat is here, the piece of code that uses nmap, NmapWrapper module, is gpl

**OScanner (www.cqure.net - Patrik Karlsson):**  he give me the idea to make what's Scylla now :)

**MSF (www.metasploit.com - HD Moore):** yup, most of default passwords and dicts are taken from there

**Compact View (http://sourceforge.net/p/compactview/home/Home/ - Iván Costales Suárez :** got some regex and the idea to make sqlbrowser

**Hydra (http://www.thc.org/thc-hydra/ - Van Hauser):** This tool really rulz! i didn't know they updated it but you should try it. The idea, and also some modules (like telnet and ftp) are based on it

**SQLMap (http://sqlmap.org/ - Bernardo):** got the UDF's from him

**FGdump (http://www.foofus.net/~fizzgig/fgdump/ - Fizzgig):** fgdump

There's also a lot of code / tools taken from other sides, the references are in the code


I'm preaty sure all (or most) of the developers got a mail from me asking if i can use their code / tool / lib