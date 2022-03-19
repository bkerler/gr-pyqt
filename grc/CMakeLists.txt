# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.

install(FILES
    pdu_lambda.block.yml
    stream_lambda.block.yml
    time_plot.block.yml
    raster_plot.block.yml
    time_hist.block.yml
    set_title.block.yml
    value_plot.block.yml
    value_hist.block.yml
    const_plot.block.yml
    ctime_plot.block.yml
    cpsd_plot.block.yml
    cpower_plot.block.yml
    pdu_meta_extract.block.yml
    text_input.block.yml
    select_input.block.yml
    variable_text_input.block.yml
    range_input.block.yml
    text_output.block.yml
    meta_text_output.block.yml
    skip_head.block.yml
    head.block.yml
    trim_tail.block.yml
    file_message_source.block.yml
    file_message_sink.block.yml
    file_open.block.yml
    dict_ui_source.block.yml
    pyqt_table.block.yml DESTINATION share/gnuradio/grc/blocks
)
