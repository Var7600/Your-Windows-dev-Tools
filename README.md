# Windows-Dev-Tools

<img src="readme-images/developer_tools.jpg" alt="Dev Tools" width="600" weigth="150" >

# Motivation

When you set up a new Windows PC, you have to install a bunch of basic software. Examples are a browser, PDF reader, text editor, zipping program, and so on. Doing this frequently gets exhausting, especially when you also have to administer devices for your friends and family.

Luckily, with [Chocolatey](https://chocolatey.org/) there is a package manager for Windows. It allows you to install and update most of the software you know directly from the command line.

> I created a PowerShell script for Chocolatey which installs common freeware applications and optionally tools for more advanced uses, like git and VS Code. All fully customizable.

*With this script, you can set up a **your software tools within minutes.**

# Included Applications

All applications are very common freeware, so I refer you to the corresponding websites for further explanation. 

Which of the apps are to be installed can be fully customized and extended. Simply delete, **uncomment or add lines in the script.**

### Developer Application Bundle

<table class="tg">
<thead>
  <tr>
    <th class="tg-8l38">Category</th>
    <th class="tg-8l38" style="width: 33%;">Applications</th>
    <th class="tg-8l38">Comments</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-z8l7">Windows utilities tools</td>
    <td class="tg-8l38">
         <img src="readme-images/1a.png"><a href="https://learn.microsoft.com/en-us/windows/powertoys/"> PowerToys</a><br/>
    </td>
    <td class="tg-8l38">
        Microsoft PowerToys is a set of utilities for power users to tune and streamline their Windows experience for greater productivity.
    </td><br/>
    <tr>
    <td class="tg-z8l7">Productivity</td>
    <td class="tg-8l38">
         <img src="readme-images/1a.png"><a href="https://ferdium.org/"> Ferdium</a><br/>
    </td>
    <td class="tg-8l38">
         Ferdium is a desktop app that helps you organize how you use your favourite apps by combining them into one application.
    </td><br/>
    </tr>
    <td class="tg-z8l7">Media Viewers</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://www.7-zip.org/"> 7zip</a><br/>
        <img src="readme-images/1a.png"><a href="https://acrobat.adobe.com/us/en/acrobat/pdf-reader.html"> Adobe Reader</a><br/>
 <img src="readme-images/1a.png"><a href="https://okular.kde.org/download/"> okular</a><br/>
        <img src="readme-images/0.png"><a href="https://www.foxitsoftware.com/pdf-reader/"> Foxit Reader</a><br/>
    </td>
    <td class="tg-8l38">Common freewares for all media formats (images & movies), texts files, .zips, .raws, and PDFs.<br>For PDFs you can stick with the default Adobe Reader or alternatively choose Foxit Reader (my recommendation).</td>
  </tr>
  <tr>
    <td class="tg-z8l7">Browsers</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://www.google.com/intl/en_us/chrome/"> Google Chrome</a><br/>
        <img src="readme-images/1a.png"><a href="https://brave.com/">Brave</a><br/>
        <img src="readme-images/1a.png"><a href=""> Waterfox</a><br/>
        <img src="readme-images/1a.png"><a href="https://www.opera.com"> Opera</a><br/>
 <img src="readme-images/1a.png"><a href="https://vivaldi.com/download/"> Vivaldi</a><br/>
  <img src="readme-images/1a.png"><a href="https://minbrowser.org/"> Min Browser</a><br/>
 <img src="readme-images/1a.png"><a href="https://www.torproject.org/download/"> TorBrowser</a><br/>
    </td>
    <td class="tg-8l38">Google Chrome , Brave ,Waterfox, Min ,Opera, ViValdi , TorBrowser</td>
  </tr>
  <tr>
    <td class="tg-z8l7">Editor,IDE</td>
    <td class="tg-8l38">
    <br/>
    <img src="readme-images/1a.png"><a href="https://notepad-plus-plus.org/"> Notepad++</a><br/>
    <img src="readme-images/1a.png"><a href="https://www.vim.org/download.php">Vim</a><br/>
     <img src="readme-images/1a.png"><a href="https://www.eclipse.org/downloads/"> Eclipse </a><br/>
     <img src="readme-images/1a.png"><a href="https://www.jetbrains.com/"> intellijidea-community </a><br/>
      <img src="readme-images/1a.png"><a href="https://netbeans.apache.org/"> Apache NetBeans </a><br/>
     <img src="readme-images/1a.png"><a href="">Bluefish</a><br/>
     <img src="readme-images/1a.png"><a href="https://www.codeblocks.org/">Codeblocks</a><br/>
       <br/>
    </td>
    <td class="tg-8l38"><b>Text Editor Notepad++ , JAVA IDE(Eclipse |ApacheNetBeans | IntelliJ),CodeBlocks(C/C++)</b></td>
  </tr>
  <tr>
    <td class="tg-z8l7">Collaboration</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://zoom.us"> Zoom</a><br/>
        <img src="readme-images/1a.png"><a href="https://discord.com/"> Discord</a><br/>
    </td>
    <td class="tg-8l38">Zoom  video conference tools (both personal and corporate).Zoom may be not allowed in your company, in this case, you should disable it. Discord is for all the tech-people out there (disabled by default)</td>
  </tr>
  <tr>
    <td class="tg-z8l7">System administration</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://chocolatey.org/packages/ChocolateyGUI"> Chocolatey GUI</a><br/>
    <td class="tg-8l38">chocolatey graphical user interface.</td>
  </tr>
  <tr>
    <td class="tg-z8l7">Encryption</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://www.veracrypt.fr/en/Home.html"> Veracrypt</a><br/>
    </td>
    <td class="tg-8l38">KeePass is a lean open-source password manager. VeraCrypt is the successor of TrueCrypt (hard disk encryption).</td>
  </tr>
  <tr>
    <td class="tg-z8l7">Tools</td>
    <td class="tg-8l38">
    <img src="readme-images/1a.png"><a href="https://www.gnu.org/software/wget/"> Wget</a><br/>
        <img src="readme-images/1a.png"><a href="https://git-scm.com/"> git</a><br/>
        <img src="readme-images/1a.png"><a href="https://www.apachefriends.org/download.html"> XAMPP</a><br/>
    <img src="readme-images/1a.png"><a href="https://zealdocs.org/"> Zeal</a><br/>
   <img src="readme-images/1a.png"><a href="https://maven.apache.org/"> Maven</a><br/>
    </td>
    <td class="tg-8l38">Wget command line tool for for retrieving files using HTTP, HTTPS, FTP and FTPS,Git for code management via git.
    XAMPP for Web server, Maven, Zeal for docsets and more(<b>curl,make,nsis,openssl,ditto</b>...)  </td>
  </tr>
  <tr>
    <td class="tg-z8l7">Programming Languages</td>
    <td class="tg-8l38">
        <img src="readme-images/1a.png"><a href="https://docs.conda.io/en/latest/miniconda.html"> Anaconda (Miniconda)/Python3</a><br/>
        <img src="readme-images/1a.png"><a href="https://www.java.com/download/ie_manual.jsp"> openJDK(java)</a><br/>
        <img src="readme-images/1a.png"><a href="https://www.mingw-w64.org/downloads/">C/C++</a><br/>
        <img src="readme-images/1a.png"><a href="https://www.php.net/downloads.php"> PHP</a><br/>
        <img src="readme-images/1a.png"><a href="https://nodejs.org/">Node.js</a><br/>
        <img src="readme-images/1a.png"><a href="https://github.com/dotnet/core"> DotNet Core</a><br/>
         <img src="readme-images/1a.png"><a href="https://go.dev/">Golang</a><br/>
    </td>
    <td class="tg-8l38">Since <b>Python</b> is very common, <b>Miniconda</b> is the small version of Anaconda (without the bulk software). <b>Java SDK, C/C++, PHP , Nodejs , R for statistical Computing,Golang</b> .</td>
  </tr>
  <tr>
   <td class="tg-z8l7">Electronics</td>
   <td class="tg-8l38">
   <img src="readme-images/1a.png"><a href="https://docs.conda.io/en/latest/miniconda.html">Logisim</a><br/>
   <td class="tg-8l38"> Logisim is a toolbar interface and simulation of circuits as you build them, it is simple enough to facilitate learning the most basic concepts related to logic circuits. With the capacity to build larger circuits from smaller subcircuits, and to draw bundles of wires with a single mouse drag, Logisim can be used to design and simulate</td>
  </tr>
  <tr>
      <td class="tg-z8l7">DataBase</td>
      <td class="tg-8l38"> <img src="readme-images/1a.png"><a href="https://dev.mysql.com/downloads/installer/">Mysql</a></td>
      <td class="tg-8l38">MySQL Community Edition is the freely downloadable version of the world's most popular open source database. It is available under the GPL license and is supported by a huge and active community of open source developers.</td>
  </tr>
</tbody>
</table>
<br/>

### Download and Run script

1. Clone this repo or download the .zip (then unzip the folder).
2. Navigate to the downloaded folder and open up the script `install-choco.ps1` in *Edit* Mode (right-click menu)
3. Enable or disable needed applications. The `#` sign comments a line out (disables it), deleting the leading `#` sign enables the line. See also [section below](#script-content).
4. Save and close.

### Execute Script

1. Open PowerShell as admin (`Win` +  `X` and select `PowerShell (Admin)`) and navigate to the downloaded folder.
2. Run the script `install-choco.ps1`. If you should get an error, then local scripts are disabled on your machine. To enable them, type  
   `Set-ExecutionPolicy UnRestricted` in PowerShell(Admin)
3. Wait and grab your **software** :)

You probably want to tidy up your [Windows Explorer right-click menu](https://www.howtogeek.com/howto/windows-vista/how-to-clean-up-your-messy-windows-context-menu/).

If you have questions, just contact me.

# Script Content

  The PowerShell script consists of a dictionary that contains the applications to install and their customized parameters (if needed). An example of a custom parameter is a different install location or the creation of a desktop shortcut.

<img src="readme-images/dict.png" width="420" />

  There is one dictionary for basic applications and one for development applications. The dictionary is selected on user-startup.

--------------

<span>Photograph by <a href="https://unsplash.com/@crj2day?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Casey Johnson</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a>.</span>
Image montage by me.
