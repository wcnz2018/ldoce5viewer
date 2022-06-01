# LDOCE5 Viewer for Big Sur

Download from release, or build it yourself:
1. Clone this repo to you mac
2. Make sure you have `brew` installed, otherwise visit: https://brew.sh/
3. Open terminal, execute command line by line:  
  `brew install python3`  
  `pip3 install -U PyQt5 py2app whoosh lxml mp3play PyObjC`   
  `cd ldoce5viewer`   
  `python3 setup.py py2app` # now you should have LDOCE5 Viewer.app under folder dist    
  `cd dist/LDOCE5\ Viewer.app/Contents/Frameworks/QtWebEngineCore.framework/Helpers/QtWebEngineProcess.app/Contents`    
  `ln -s ../../../../../../../Frameworks .`  
  `cd -` 
4. Check if your new build is working by launching it from command line, if not it will tell you why:  
  `./dist/LDOCE5\ Viewer.app/Contents/MacOS/LDOCE5\ Viewer`
5. Relocate your build if it works:
  `mv ./dist/LDOCE5\ Viewer.app /Applications`   
  
All credits go to the original author.  
