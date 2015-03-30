# Introduction #

  1. o install
> sh jdk-6u21-linux-x64.bin
> cp -r jdk1.6.0\_21/ /usr/local/
> ln -s /usr/local/jdk1.6.0\_21/ /usr/local/jdk

> export JAVA\_HOME=/usr/local/jdk
> export PATH=$PATH:$JAVA\_HOME/bin

> wget wget http://downloads.sourceforge.net/project/jpype/JPype/0.5.4/JPype-0.5.4.1.zip?r=http%3A%2F%2Fsourceforge.net%2Fprojects%2Fjpype%2Ffiles%2FJPype%2F0.5.4%2F&ts=1291381165&use_mirror=jaist
> unzip JPype-0.5.4.1.zip
> cd JPype-0.5.4.1

  1. if install faild path change
  1. ##vi setup.py
  1. ##vi src/python/jpype/_linux.py_

> python setup.py install

  1. o monitring
> python get\_cassandra\_XXX.py #etc...

  1. heck
> http://wiki.apache.org/cassandra/JmxInterface
> """


# Details #

Add your content here.  Format your content with:
  * Text in **bold** or _italic_
  * Headings, paragraphs, and lists
  * Automatic links to other wiki pages