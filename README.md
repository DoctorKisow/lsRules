# i-BlockList for Little Snitch
**i-BlockList** - i-BlockList Rule Group Subscriptions.  
Matthew R. Kisow, D.Sc. <matthew.kisow@kisow.org>  
Copyright &copy; Kisow Foundation, Inc.&reg; 2019-2020.  

## Getting Started
i-BlockList Rule Group Subscriptions.</br>
This script will pull different blocklists from i-Blocklist and parse them into LittleSnitch lsRules JSON format.  The rule files must then be published to a URL location for download into LittleSnitch.

## lsRules Git Structure
```shell
     lsRules  
     |--  master  
     |    |--  lsRules        (Shell Script)
     |    |--  lsRules.cfg    (Configuration File)
     |    |--  README.md      (This File)  
     |    |--  LICENSE        (GPL v3.0)
     |    |--  *.lsRules      (Little Snitch Rules)
     |
```

## Installation
1. From LittleSnitch add the rule group subscription of your choice:
```shell
     https://raw.githubusercontent.com/DoctorKisow/lsRules/master/<rule name>.lsrules
```
## Updating
1. Set rule updates to manual or automatic:

## License
License (GPL v3.0)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.