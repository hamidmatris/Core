# Copyright (C) 2008-2013 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Custom/VendorScript.cpp
  Custom/UtilityCmd.cpp
  Custom/Supporter.cpp
  Custom/Teleporter.cpp
  Custom/GurubashiEvent.cpp
  Custom/Transmogrification.h
  Custom/Transmogrification.cpp
  Custom/ArenaFastStart.cpp
  Custom/ArenaSpectate.cpp
  Custom/ChangeToken.cpp
  Custom/PvPIsleScript.cpp
  Custom/Item.cpp
  Custom/Arena_Scripts.cpp
  Custom/Profession_NPC.cpp
  Custom/event.cpp
  Custom/Enchanter.cpp
  Custom/chat.cpp
  Custom/DuelCD.cpp
  Custom/npc_arena_team_top.cpp
  Custom/class.cpp
  Custom/hunterpet_vendor.cpp
  Custom/1v1.cpp
  Custom/Transmog.cpp
)

message("  -> Prepared: Custom")
