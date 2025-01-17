# Copyright 2011 Free Software Foundation, Inc.
#
# This file was generated by gr_modtool, a tool from the GNU Radio framework
# This file is a part of gr-pyqt
#
# SPDX-License-Identifier: GPL-3.0-or-later
#

########################################################################
# Include python install macros
########################################################################
include(GrPython)
if(NOT PYTHONINTERP_FOUND)
    return()
endif()

add_subdirectory(bindings)

########################################################################
# Install python sources
########################################################################
GR_PYTHON_INSTALL(
    FILES
    __init__.py
    pdu_lambda.py
    set_title.py
    stream_lambda.py
    const_plot.py
    ctime_plot.py
    raster_plot.py
    value_plot.py
    value_hist.py
    cpsd_plot.py
    time_plot.py
    time_hist.py
    cpower_plot.py
    plotter_base.py
    pdu_meta_extract.py
    text_input.py
    select_input.py
    variable_text_input.py
    range_input.py
    text_output.py
    meta_text_output.py
    head.py
    skip_head.py
    trim_tail.py
    file_message_source.py
    file_message_sink.py
    file_open.py
    dict_ui_source.py
    table.py
    DESTINATION ${GR_PYTHON_DIR}/pyqt
)

########################################################################
# Handle the unit tests
########################################################################
include(GrTest)

set(GR_TEST_TARGET_DEPS gnuradio-pyqt)
