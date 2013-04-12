FPGA Stereo Vision
==================

The FPGA stereo vision project's goal is to design and implement a stereo vision
system on a field-programmable gate array (FPGA) to allow robots to detect and
process their surroundings.

Installation
------------

    $ git clone git://github.com/kylc/fpga_stereo_vision

Examples
--------

Core test:

    $ make compile_stereobm_core_tb
    $ ./stereobm_core_tb

Prefilter test:

    $ make compile_stereobm_prefilter_tb
    $ ./stereobm_prefilter_tb
