Sparky SU
This package provides Yad based front-end for su (spsu) allowing users to give a password and run graphical commands as root without needing to invoke su in a terminal emulator, and spsudo to run an application as a super user.

Copyright (C) 2018-2020 Paweł Pijanowski

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
coreutils
empty-expect
grep
login
sed
sparky-pass-check
sudo
x11-xserver-utils
yad

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
