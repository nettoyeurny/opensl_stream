opensl_stream
=============

A simple callback-driven audio API for Android that sits on top of OpenSL and provides a credible illusion of synchronized input and output.

Make sure to include "-lOpenSLES -llog" in LOCAL_LDLIBS.

This library only requires Android 2.3 or later, i.e., it will work on all Android devices that support OpenSL.

Sample code, including Java code for properly configuring OpenSL: https://github.com/nettoyeurny/opensl_stream_sample
