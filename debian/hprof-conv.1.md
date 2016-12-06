% HPROF-CONV(1) android-platform-dalvik | hprof-conv Manuals
% The Android Open Source Project
% 6.0.1_r16

# NAME

hprof-conv - HPROF Converter

# SYNOPSIS

**hprof-conf** [-z] _infile_ _outfile_

# DESCRIPTION

The **hprof-conv** tool converts the HPROF file that is generated by the Android
SDK tools to a standard format so you can view the file in a profiling tool of
your choice.

# OPTIONS

-z
: Filter out zygote allocations shared by all applications.

You can use **-** for _infile_ or _outfile_ to specify **stdin** or **stdout**.

# SEE ALSO

https://developer.android.com/tools/help/hprof-conv.html