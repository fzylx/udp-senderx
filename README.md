# UdpSenderX

UdpSenderX is [Udpcast's](http://www.udpcast.linux.lu/) udp-sender with support for sending multiple files as one without using a shell.

```shell
  udp-sender --file sda1.img.gz.aa,sda1.img.gz.ab,sda1.img.gz.ac --nokbd --min-receivers 5 --min-wait 20 --max-wait 80
```


## License
   udpcast and its FEC code are free software

   you can redistribute udpcast core functionality and/or
   it them under the terms of the GNU General Public License as
   published by the Free Software Foundation; either version 2 of
   the License, or (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.

   You should have received a copy of the GNU General Public License
   along with this program; see the file COPYING.
   If not, write to the Free Software Foundation, Inc.,
   59 Temple Place - Suite 330, Boston, MA 02111-1307, USA.

   Alain Knaff
   <alain@knaff.lu>
   http://udpcast.linux.lu/

the FEC code is covered by the following license:
fec.c -- forward error correction based on Vandermonde matrices
980624
(C) 1997-98 Luigi Rizzo (luigi@iet.unipi.it)
(C) 2001 Alain Knaff (alain@knaff.lu)

Portions derived from code by Phil Karn (karn@ka9q.ampr.org),
Robert Morelos-Zaragoza (robert@spectra.eng.hawaii.edu) and Hari
Thirumoorthy (harit@spectra.eng.hawaii.edu), Aug 1995

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above
   copyright notice, this list of conditions and the following
   disclaimer in the documentation and/or other materials
   provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE AUTHORS ``AS IS'' AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHORS
BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY,
OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA,
OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR
TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT
OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY
OF SUCH DAMAGE.

