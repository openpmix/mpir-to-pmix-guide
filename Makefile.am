#
# Copyright 2020     Intel, Inc. All rights reserved
# Copyright (c) 2020      IBM Corporation.  All rights reserved.
# $COPYRIGHT$
#
# Additional copyrights may follow
#
# $HEADER$
#
# See COPYING in top-level directory.

# Note that the -I directory must *exactly* match what was specified
# via AC_CONFIG_MACRO_DIR in configure.ac.
ACLOCAL_AMFLAGS = -I ./config

#
# "make distcheck" requires that tarballs are able to be able to "make
# dist", so we have to include config/distscript.sh.
#
EXTRA_DIST = \
        README.md VERSION COPYING AUTHORS \
        config/mpirshim_get_version.sh

SUBDIRS = src test
