<div align="center">

## Make your own Java IDE


</div>

### Description

Make your own IDE using Batch Script. Just Copy-Paste the given code to a notepad and rename it as "Java File Maker.bat" and "Java Applet Maker.bat".
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Chanchal Kumar Ghosh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chanchal-kumar-ghosh.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\), Java \(JDK 1\.3\), Java \(JDK 1\.4\), Java \(JDK 1\.5\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chanchal-kumar-ghosh-make-your-own-java-ide__2-6667/archive/master.zip)





### Source Code

<h1>Java File Maker.bat:</h1><br/>
<style type="text/css">
span {
	font-family: 'Courier New';
	font-size: 10pt;
	color: #000000;
}
.sc0 {
}
.sc2 {
	font-weight: bold;
	color: #0000FF;
}
.sc3 {
	font-weight: bold;
	color: #FF0000;
	background: #FFFF80;
}
.sc4 {
	color: #FF00FF;
}
.sc5 {
	color: #0080FF;
}
.sc6 {
	font-weight: bold;
	color: #FF8000;
	background: #FCFFF0;
}
.sc7 {
	font-weight: bold;
	color: #FF0000;
}
</style>
<div style="white-space: pre; line-height: 1; background: #FFFFFF; "><span class="sc4">@</span><span class="sc2">ECHO</span><span class="sc0"> OFF
</span><span class="sc2">SET</span><span class="sc0"> yourname</span><span class="sc7">=</span><span class="sc0">Chanchal Kumar Ghosh
</span><span class="sc2">SET</span><span class="sc0"> email</span><span class="sc7">=</span><span class="sc0">chanchal_ghosh1987@yahoo.co.in
</span><span class="sc2">SET</span><span class="sc0"> version</span><span class="sc7">=</span><span class="sc0">1.0.0
</span><span class="sc5">COLOR</span><span class="sc0"> F0
</span><span class="sc5">TITLE</span><span class="sc0"> Java File Maker
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">               Java File Maker
</span><span class="sc2">ECHO</span><span class="sc0">               Version </span><span class="sc6">%version%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">           Made by </span><span class="sc6">%yourname%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">         Email:</span><span class="sc6">%email%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">PAUSE</span><span class="sc0">
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">SET</span><span class="sc0"> /P filename</span><span class="sc7">=</span><span class="sc0">Enter Java file name :
</span><span class="sc2">IF EXIST</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
  </span><span class="sc5">(GOTO</span><span class="sc0"> FILEEXIST
  )</span><span class="sc2">ELSE</span><span class="sc0"> (
    </span><span class="sc2">IF EXIST</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc2"> GOTO</span><span class="sc0"> DIREXIST
  )
</span><span class="sc2">MKDIR</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">
</span><span class="sc3">:DIREXIST
</span><span class="sc2">ECHO</span><span class="sc0"> /</span><span class="sc7">*****************************************************&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Program </span><span class="sc6">%filename%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Made by </span><span class="sc6">%yourname%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Email: </span><span class="sc6">%email%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Made at </span><span class="sc6">%DATE%</span><span class="sc0"> </span><span class="sc6">%TIME%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> </span><span class="sc7">******************************************************</span><span class="sc0">/</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> class </span><span class="sc6">%filename%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> {</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     public static void main(String args[])</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     {</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     }</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> }</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc3">:FILEEXIST
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> choice</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">        FILE: </span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Enter your choice and then press 'Enter':
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">         1. Edit File
</span><span class="sc2">ECHO</span><span class="sc0">         2. Compile and Run
</span><span class="sc2">ECHO</span><span class="sc0">         3. Open File Location
</span><span class="sc2">ECHO</span><span class="sc0">         4. Exit
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">SET</span><span class="sc0"> /P choice</span><span class="sc7">=</span><span class="sc0">Enter Choice :
</span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">1</span><span class="sc5"> (</span><span class="sc0">
  </span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
  </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
  )</span><span class="sc2">ELSE</span><span class="sc0"> (
  </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">2</span><span class="sc5"> (</span><span class="sc0">
    </span><span class="sc2">GOTO</span><span class="sc0"> COMPILE
    )</span><span class="sc2">ELSE</span><span class="sc0"> (
    </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">3</span><span class="sc5"> (</span><span class="sc0">
      </span><span class="sc5">START explorer</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\
      </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
      )</span><span class="sc2">ELSE</span><span class="sc0"> (
      </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">4</span><span class="sc5"> (</span><span class="sc0">
        </span><span class="sc2">GOTO</span><span class="sc0"> EXIT
      )</span><span class="sc2">ELSE</span><span class="sc0"> (
        </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
      )
    )
  )
)
</span><span class="sc3">:COMPILE
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Error and Wornings:
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc5">javac</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%errorlevel%</span><span class="sc7">==</span><span class="sc0">1</span><span class="sc5"> (</span><span class="sc0">
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">ECHO</span><span class="sc0"> Your files have some errors. Please Continue with editing...
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">PAUSE</span><span class="sc0">
  </span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
  </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
  )
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Output of Your Program </span><span class="sc6">%filename%</span><span class="sc0">.java:
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">CD</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">
</span><span class="sc5">java</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">
</span><span class="sc2">CD</span><span class="sc0">..
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">PAUSE</span><span class="sc0">
</span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
</span><span class="sc3">:EXIT
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">             Java File Maker(</span><span class="sc6">%version%</span><span class="sc0">)
</span><span class="sc2">ECHO</span><span class="sc0">           Made by </span><span class="sc6">%yourname%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">         Email:</span><span class="sc6">%email%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">                Thank You
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">PAUSE</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> filename</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> choice</span><span class="sc7">=</span></div>
<br/><br/><br/><h1>Java Applet Maker.bat:</h1><br/>
<div style="float: left; white-space: pre; line-height: 1; background: #FFFFFF; "><span class="sc4">@</span><span class="sc2">ECHO</span><span class="sc0"> OFF
</span><span class="sc2">SET</span><span class="sc0"> yourname</span><span class="sc7">=</span><span class="sc0">Chanchal Kumar Ghosh
</span><span class="sc2">SET</span><span class="sc0"> email</span><span class="sc7">=</span><span class="sc0">chanchal_ghosh1987@yahoo.co.in
</span><span class="sc2">SET</span><span class="sc0"> version</span><span class="sc7">=</span><span class="sc0">1.0.0
</span><span class="sc5">COLOR</span><span class="sc0"> F0
</span><span class="sc5">TITLE</span><span class="sc0"> Java Applet Maker
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">              Java Applet Maker
</span><span class="sc2">ECHO</span><span class="sc0">               Version </span><span class="sc6">%version%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">           Made by </span><span class="sc6">%yourname%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">         Email:</span><span class="sc6">%email%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">PAUSE</span><span class="sc0">
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">SET</span><span class="sc0"> /P filename</span><span class="sc7">=</span><span class="sc0">Enter Java file name :
</span><span class="sc2">IF EXIST</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java</span><span class="sc2"> GOTO</span><span class="sc0"> FILEEXIST
</span><span class="sc2">ELSE</span><span class="sc0"> (
  </span><span class="sc2">IF EXIST</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc2"> GOTO</span><span class="sc0"> DIREXIST
)
</span><span class="sc2">MKDIR</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">
</span><span class="sc3">:DIREXIST
</span><span class="sc2">ECHO</span><span class="sc0"> /</span><span class="sc7">*****************************************************&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Program </span><span class="sc6">%filename%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Made by </span><span class="sc6">%yourname%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Email: </span><span class="sc6">%email%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> Made at </span><span class="sc6">%DATE%</span><span class="sc0"> </span><span class="sc6">%TIME%</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> </span><span class="sc7">******************************************************</span><span class="sc0">/</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> import java.awt.</span><span class="sc7">*</span><span class="sc0">;</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> import java.applet.</span><span class="sc7">*</span><span class="sc0">;</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> public class </span><span class="sc6">%filename%</span><span class="sc0"> extends java.applet.Applet</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> {</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     public void paint(Graphics g)</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     {</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">     }</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> }</span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0"> ^</span><span class="sc7">&lt;</span><span class="sc0">html^</span><span class="sc7">&gt;</span><span class="sc0"> </span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.html
</span><span class="sc2">ECHO</span><span class="sc0"> ^</span><span class="sc7">&lt;</span><span class="sc0">applet code</span><span class="sc7">=</span><span class="sc6">%filename%</span><span class="sc0">.class width</span><span class="sc7">=</span><span class="sc0">400 height</span><span class="sc7">=</span><span class="sc0">200^</span><span class="sc7">&gt;</span><span class="sc0"> </span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.html
</span><span class="sc2">ECHO</span><span class="sc0"> ^</span><span class="sc7">&lt;</span><span class="sc0">/applet^</span><span class="sc7">&gt;</span><span class="sc0"> </span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.html
</span><span class="sc2">ECHO</span><span class="sc0"> ^</span><span class="sc7">&lt;</span><span class="sc0">/html^</span><span class="sc7">&gt;</span><span class="sc0"> </span><span class="sc7">&gt;&gt;</span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.html
</span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc3">:FILEEXIST
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> choice</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">        FILE: </span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Enter your choice and then press 'Enter':
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">         1. Edit File
</span><span class="sc2">ECHO</span><span class="sc0">         2. Compile and Run
</span><span class="sc2">ECHO</span><span class="sc0">         3. Open File Location
</span><span class="sc2">ECHO</span><span class="sc0">         4. Exit
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">SET</span><span class="sc0"> /P choice</span><span class="sc7">=</span><span class="sc0">Enter Choice :
</span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">1</span><span class="sc5"> (</span><span class="sc0">
  </span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
  </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
  )
</span><span class="sc2">ELSE</span><span class="sc0"> (
  </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">2</span><span class="sc5"> (</span><span class="sc0">
    </span><span class="sc2">GOTO</span><span class="sc0"> COMPILE
    )
  </span><span class="sc2">ELSE</span><span class="sc0"> (
    </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">3</span><span class="sc5"> (</span><span class="sc0">
      </span><span class="sc5">START explorer</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\
      </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
      )
    </span><span class="sc2">ELSE</span><span class="sc0"> (
      </span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%choice%</span><span class="sc7">==</span><span class="sc0">4</span><span class="sc5"> (</span><span class="sc0">
        </span><span class="sc2">GOTO</span><span class="sc0"> EXIT
      )
      </span><span class="sc2">ELSE</span><span class="sc0"> (
        </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
      )
    )
  )
)
</span><span class="sc3">:COMPILE
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Error and Wornings:
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc5">javac</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
</span><span class="sc2">IF</span><span class="sc0"> </span><span class="sc6">%errorlevel%</span><span class="sc7">==</span><span class="sc0">1</span><span class="sc5"> (</span><span class="sc0">
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">ECHO</span><span class="sc0"> Your files have some errors. Please Continue with editing...
  </span><span class="sc2">ECHO</span><span class="sc0">.
  </span><span class="sc2">PAUSE</span><span class="sc0">
  </span><span class="sc5">START notepad</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">\</span><span class="sc6">%filename%</span><span class="sc0">.java
  </span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
  )
</span><span class="sc2">CLS</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0"> Exicuting...
</span><span class="sc2">CD</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">
</span><span class="sc5">appletviewer</span><span class="sc0"> </span><span class="sc6">%filename%</span><span class="sc0">.html
</span><span class="sc2">CD</span><span class="sc0">..
</span><span class="sc2">GOTO</span><span class="sc0"> FILEEXIST
</span><span class="sc3">:EXIT
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">            Java Applet Maker(</span><span class="sc6">%version%</span><span class="sc0">)
</span><span class="sc2">ECHO</span><span class="sc0">           Made by </span><span class="sc6">%yourname%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">         Email:</span><span class="sc6">%email%</span><span class="sc0">
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">                Thank You
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">ECHO</span><span class="sc0">.
</span><span class="sc2">PAUSE</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> yourname</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> email</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> version</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> filename</span><span class="sc7">=</span><span class="sc0">
</span><span class="sc2">SET</span><span class="sc0"> choice</span><span class="sc7">=</span></div>
<br/></br/>

