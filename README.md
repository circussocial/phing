P     H     I     N     G
=========================



  (PH)ing (I)s (N)ot (G)NU make; it's a PHP project build system or build
  tool based on Apache Ant. You can do anything with it that you could do
  with a traditional build system like GNU make, and its use of simple XML
  build files and extensible PHP "task" classes make it an easy-to-use and
  highly flexible build framework.

  Features include running PHPUnit and SimpleTest unit tests (including test
  result and coverage reports), file transformations (e.g. token replacement,
  XSLT transformation, Smarty template transformations),
  file system operations, interactive build support, SQL execution,
  CVS/SVN/GIT operations, tools for creating PEAR packages, documentation
  generation (DocBlox, PhpDocumentor) and much, much more.

  If you find yourself writing custom scripts to handle the packaging,
  deploying, or testing of your applications, then we suggest looking at Phing.
  Phing comes packaged with numerous out-of-the-box operation modules (tasks),
  and an easy-to-use OO model to extend or add your own custom tasks.

  Phing provides the following features:

  * Simple XML buildfiles
  * Rich set of provided tasks
  * Easily extendable via PHP classes
  * Platform-independent: works on UNIX, Windows, Mac OSX
  * No required external dependencies
  * Built for PHP5

The Latest Version
------------------

  Details of the latest version can be found on the Phing homepage
  <http://www.phing.info/>.

Installation
------------

 If you are using Phing in conjunction with another application, you may need to add additional paths to PHP_CLASSPATH.

Unix

Assuming you are running a Unix dialect operating system with the bash bourne shell and Phing is installed in /opt/phing . The following sets up the environment properly:

  export PHP_COMMAND=/usr/bin/php
  
  export PHING_HOME=/opt/phing
  
  export PHP_CLASSPATH=${PHING_HOME}/classes
  
  export PATH=${PATH}:${PHING_HOME}/bin
  
  
  
Windows

On the Windows platfrom, assuming Phing is installed in c:\opt\phing. The following sets up your environment:

  set PHP_COMMAND=c:\opt\php\php.exe
  
  set PHING_HOME=c:\opt\phing
  
  set PHP_CLASSPATH=c:\opt\phing\classes
  
  set PATH=%PATH%;%PHING_HOME%\bin
  
Advanced

There are lots of variants that can be used to run/prepare Phing. You need at least the following:

If you want Phing to be able to use other packages / classes, you can either add them to the PHP_CLASSPATH or to PHP's include_path.
Some Tasks in phing/tasks/ext may require 3rd party libraries to be installed. Generally, tools with compatible license (and stable releases) are included in phing/lib so that outside dependencies can be avoided. PEAR libs will not, however, be bundled with Phing since they are generally bundled with PHP. If you are using a 3rd party task, see the Task documentation to be aware of any dependencies.
You are now ready to use the phing command at your command prompt, from everywhere in your directory tree.

Calling Phing

Now you are prepared to execute Phing on the command line or via script files. The following section briefly describe how to properly execute phing.



Documentation
-------------

  Documentation is available in various formats in the *docs/docbook5/en/output*
  directory (generated from DocBook sources located in *docs/docbook5/en/source*).

  Additionally, the legacy user guide can be found in *docs/phing_guide*.

  For online documentation, you can also visit the Phing website: http://www.phing.info/

Licensing
---------

  This software is licensed under the terms you may find in the file
  named "LICENSE" in this directory.

  Thank you for using PHING!

Contact
-------

  * Twitter: [@phingofficial](http://twitter.com/phingofficial)
  * Website: [http://www.phing.info](http://www.phing.info)
  * IRC:     Freenode, #phing
  * GitHub:  [https://www.github.com/phingofficial/phing](https://www.github.com/phingofficial/phing)
  * E-mail:  [dev-subscribe@phing.tigris.org](mailto:dev-subscribe@phing.tigris.org) (mailing list)

PhpStorm License
----------------

  If you are contributing code to the Phing project and want to use PhpStorm for
  development feel free to ask Ben (bschultz.bb@gmail.com) for our Open Source License.

  Proud to use:

  [![PhpStorm Logo](http://www.jetbrains.com/phpstorm/documentation/phpstorm_banners/phpstorm1/phpstorm468x60_violet.gif "Proud to use")](http://www.jetbrains.com/phpstorm)

  Intelligent PHP IDE for coding, testing and debugging with pleasure
