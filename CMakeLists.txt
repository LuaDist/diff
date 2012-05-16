# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Kapec, Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( diff NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

# Install all files and documentation
install_lua_module ( diff lua/diff.lua )
install_data ( LICENSE.txt )
install_doc ( doc/ )
install_test ( tests/ )
