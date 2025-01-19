# Table of Contents:
#	1. Terminology
#	2. Naming Schema
#
# ----------------------------------------------------------------------
#
# 1. Terminology
#
# Condensed Army:
#	Any army that is added by this mod
#	For example, pmca_ten_tec_reanimator
#
# Source army:
#	Any army that was used to generated Condensed Armies
#	For example, the vanilla clone_army is the Source army for pmca_ten_clone_army and pmca_hundred_clone_army
#
# Conditional Inline:
#	So long story short, TTFTCUTS realized that you can do some funky math with inline_scripts to selectively load content.
#	This is fantastic as it allows me (and others) to support other mods w/o needing having to spam the error log or need a separate mod.
#	The only downside is that it requires the mod you want to support to have a non-zero scripted_variable to check for, but thankfully making a new
#	scripted_variable is really easy (like 1 minute max).
#
# ----------------------------------------------------------------------
#
# 2. Naming Schema
#
# Filenames start with ! so the armies they add (hopefully) sort to the top of the recruitment UI
#
# The next four (4) numbers indicates the `category`. In order:
# 0000 <-> 0999 | Inline for one mod
# 1000 <-> 1999 | Inline for two mods
# 2000 <-> 2999 | Inline for three mods
# 3000 <-> 3999 | Inline for four mods
# 4000 <-> 4999 | Inline for five mods (Not implemented)
# 5000 <-> 5999 | Inline for six mods (Not implemented)
# 6000 <-> 6999 | Inline for seven mods (Not implemented)
# 7000 <-> 7999 | Inline for eight mods (Not implemented)
# 8000 <-> 8999 | Inline for nine mods (Not implemented)
# 9000 <-> 9999 | Inline for ten mods (Not implemented)
#
# The 'pmca' is just a common acronym I use a lot of stuff in this mod, like how Gigastructures uses 'giga' or Ancient Cache of Technologies uses 'acot'
#
# The final part of the filename is for easy identification of what mod the file handles
#
# @SgtPeppersSoul I've formatted army costs as more "elite" armies get a higher energy upkeep, while armies that are "bigger" cost more armaments. I'll take a look, though.
