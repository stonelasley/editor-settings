# editor-settings
An attempt at syncing Webstorm and Visual Studio keybindings. 

### Prerequisites
  - [Resharper](https://www.jetbrains.com/resharper/download/) 
  - [IdeaVim](https://plugins.jetbrains.com/plugin/164?pr=idea)
  - [VsVim](https://visualstudiogallery.msdn.microsoft.com/59ca71b3-a4a3-46ca-8fe1-0e90e3f79329)
  
### Keybinds
|Action      	            | VS  	                            | WS                                | Vim  	|   	|
|---                	    |---	                            |---	                            |---	|---	|
|Global Find / Goto Type    | ALT + N	                        |ALT + N  	                        |   	|   	|
|Goto Implementation   	    |CTRL + F12   	                    |CTRL + F12   	                    |   	|   	|
|Goto Declaration   	    |F12        	                    |F12   	                            |   	|   	|
|Find Usages        	    |SHIFT + F12   	                    |SHIFT + F12   	                    |   	|   	|
|Comment Line       	    |CTRL + '/' OR CTRL + K,C           |CTRL + '/' OR CTRL + K,C           |   	|   	|
|Format Code        	    |CTRL + K,D OR ALT + F8	            |CTRL + K,D OR ALT + F8     |   	|   	|
|Goto Symbol   	            |SHIFT + ALT + N                   	|SHIFT + ALT + N              	    |   	|   	|
|Goto Base/Super            |ALT + HOME   	                    |ALT + HOME   	                    |   	|   	|
|Goto Start/End code block  |CTRL + SHIFT + M OR CTRL + ']'   	|CTRL + SHIFT + M OR CTRL + ']'  	|   	|   	|
|Increase Decrease Font   	|CTRL + Scroll   	                |CTRL + Scroll  	                |   	|   	|
|Delete Line   	            |CTRL + SHIFT + L   	            |CTRL + SHIFT + L  	                |d,d   	|
|Extract/Intro Field        |CTRL + R,F    	                    |CTRL + R,F  	                    |   	|   	|
|Extract/Intro Variable     |CTRL + R,V    	                    |CTRL + R,V  	                    |   	|   	|
|Extract/Intro Parameter    |CTRL + R,P    	                    |CTRL + R,P  	                    |   	|   	|
|Extract/Intro Constant     |           	                    |CTRL + R,C  	                    |   	|   	|
|Extract Interface         	|CTRL + R,I   	                    |CTRL + R,I                       	|   	|   	|
|Extract Method            	|CTRL + R,M   	                    |CTRL + R,M                        	|   	|   	|
|Refactor Rename           	|CTRL + R,R   	                    |                                  	|   	|   	|


### Notes
1. Key bindings such as CTRL + A,B are also setup as CTRL + A, CTRL + B so the second control isn't strictly necessary. 
2. This currently comes with some of my javascript and typescript live templates 
3. This is a pretty niche project but if you come across it and have improvements please shoot me a pull request.
4. If a Keybinding isn't listed it hasn't been changed


