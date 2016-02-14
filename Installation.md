
---


# Contents #



---


# Dependencies #


## Linux ##

### Required ###

  * [Python](http://www.python.org/) v3, [Qt4](http://www.trolltech.com/products/qt), [PyQt4](http://www.riverbankcomputing.co.uk/software/pyqt/intro), [Make](http://www.gnu.org/software/make/), [Grep](http://www.gnu.org/software/grep/), [Fcron](http://fcron.free.fr/)

#### PyQt4 ####

  * This application requires that PyQt4 is built for (bound to) Python v3.
  * The standard 'pyqt4' package on your system was probably built for Python v2.
  * Ask your Linux distribution developers to create a "PyQt4 for Python v3" package.

### Recommended ###

  * [KdeSudo](http://kde-apps.org/content/show.php/KdeSudo?content=72106)
    * Ensure that [Sudo](http://www.gratisoft.us/sudo/) is working before installing KdeSudo.


---


# Installation #


## Linux ##

Ensure that you've installed the applications listed in the above 'Dependencies' section first.

### Configure ###

#### Fcron ####

### Build ###

```
cd Build
make all
```

### Install ###

#### System ####
```
cd Build
sudo make install
```

#### User ####
```
cd Build
make install-user
```

Add `$HOME/bin/` to the `$PATH` variable in your `~/.bash_profile` or equivalent and restart KDE.

### Proxy ###

The proxy server defined by your `$http_proxy` environment variable will be used.  For example, add the following to your `~/.bash_profile` or equivalent and restart KDE:

```
export http_proxy=http://[user:password@]proxy.isp.com[:80]/
```


---


# Removal #

## Linux ##

### Uninstall ###

#### System ####
```
cd Build
sudo make uninstall
```

#### User ####
```
cd Build
make uninstall-user
```