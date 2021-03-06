#
# Copyright (C) 2005-2012 MaNGOS project <http://getmangos.com/>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#

set(LIBRARY_NAME game)

set(LIBRARY_SRCS
AccountMgr.cpp
AccountMgr.h
AchievementMgr.cpp
AchievementMgr.h
AggressorAI.cpp
AggressorAI.h
AntiCheat.cpp
AntiCheat.h
ArenaTeam.cpp
ArenaTeam.h
ArenaTeamHandler.cpp
AuctionHouseHandler.cpp
AuctionHouseMgr.cpp
AuctionHouseMgr.h
Bag.cpp
Bag.h
Calendar.cpp
Calendar.h
CalendarHandler.cpp
Camera.cpp
Camera.h
Cell.h
CellImpl.h
Channel.cpp
Channel.h
ChannelHandler.cpp
ChannelMgr.cpp
ChannelMgr.h
CharacterDatabaseCleaner.cpp
CharacterDatabaseCleaner.h
CharacterHandler.cpp
Chat.cpp
Chat.h
ChatHandler.cpp
ChatLexicsCutter.cpp
ChatLexicsCutter.h
ChatLog.cpp
ChatLog.h
CombatHandler.cpp
ConfusedMovementGenerator.cpp
ConfusedMovementGenerator.h
Corpse.cpp
Corpse.h
CreatureAI.cpp
CreatureAI.h
CreatureAIImpl.h
CreatureAIRegistry.cpp
CreatureAIRegistry.h
CreatureAISelector.cpp
CreatureAISelector.h
Creature.cpp
CreatureEventAI.cpp
CreatureEventAI.h
CreatureEventAIMgr.cpp
CreatureEventAIMgr.h
Creature.h
CreatureLinkingMgr.cpp
CreatureLinkingMgr.h
DBCEnums.h
DBCfmt.h
DBCStores.cpp
DBCStores.h
DBCStructure.cpp
DBCStructure.h
debugcmds.cpp
DuelHandler.cpp
DynamicObject.cpp
DynamicObject.h
FleeingMovementGenerator.cpp
FleeingMovementGenerator.h
FollowerReference.cpp
FollowerReference.h
FollowerRefManager.h
Formulas.h
GameEventMgr.cpp
GameEventMgr.h
GameObject.cpp
GameObject.h
GMTicketHandler.cpp
GMTicketMgr.cpp
GMTicketMgr.h
GossipDef.cpp
GossipDef.h
GridDefines.h
GridMap.cpp
GridMap.h
GridNotifiers.cpp
GridNotifiers.h
GridNotifiersImpl.h
GridStates.cpp
GridStates.h
Group.cpp
Group.h
GroupHandler.cpp
GroupReference.cpp
GroupReference.h
GroupRefManager.h
GuardAI.cpp
GuardAI.h
Guild.cpp
Guild.h
GuildHandler.cpp
GuildMgr.cpp
GuildMgr.h
HomeMovementGenerator.cpp
HomeMovementGenerator.h
HostileRefManager.cpp
HostileRefManager.h
IdleMovementGenerator.cpp
IdleMovementGenerator.h
InstanceData.cpp
InstanceData.h
Item.cpp
ItemEnchantmentMgr.cpp
ItemEnchantmentMgr.h
Item.h
ItemHandler.cpp
ItemPrototype.h
Language.h
Level0.cpp
Level1.cpp
Level2.cpp
Level3.cpp
LFG.cpp
LFG.h
LFGHandler.cpp
LFGMgr.cpp
LFGMgr.h
LootHandler.cpp
LootMgr.cpp
LootMgr.h
Mail.cpp
Mail.h
MailHandler.cpp
Map.cpp
Map.h
MapManager.cpp
MapManager.h
MapPersistentStateMgr.cpp
MapPersistentStateMgr.h
MapReference.h
MapRefManager.h
MapUpdater.cpp
MapUpdater.h
MassMailMgr.cpp
MassMailMgr.h
MiscHandler.cpp
MotionMaster.cpp
MotionMaster.h
MoveMap.cpp
MoveMap.h
MoveMapSharedDefines.h
MovementGenerator.cpp
MovementGenerator.h
MovementGeneratorImpl.h
MovementHandler.cpp
NPCHandler.cpp
NPCHandler.h
NullCreatureAI.cpp
NullCreatureAI.h
ObjectAccessor.cpp
ObjectAccessor.h
Object.cpp
ObjectGridLoader.cpp
ObjectGridLoader.h
ObjectGuid.cpp
ObjectGuid.h
Object.h
ObjectLock.h
ObjectMgr.cpp
ObjectMgr.h
ObjectPosSelector.cpp
ObjectPosSelector.h
Opcodes.cpp
Opcodes.h
PathFinder.cpp
PathFinder.h
Path.h
pchdef.cpp
pchdef.h
PetAI.cpp
PetAI.h
Pet.cpp
Pet.h
PetHandler.cpp
PetitionsHandler.cpp
Player.cpp
PlayerDump.cpp
PlayerDump.h
Player.h
PointMovementGenerator.cpp
PointMovementGenerator.h
PoolManager.cpp
PoolManager.h
QueryHandler.cpp
QuestDef.cpp
QuestDef.h
QuestHandler.cpp
RandomMovementGenerator.cpp
RandomMovementGenerator.h
ReactorAI.cpp
ReactorAI.h
ReputationMgr.cpp
ReputationMgr.h
ScriptMgr.cpp
ScriptMgr.h
SharedDefines.h
SkillHandler.cpp
SocialMgr.cpp
SocialMgr.h
SpellAuraDefines.h
SpellAuras.cpp
SpellAuras.h
SpellClassMask.h
Spell.cpp
SpellEffects.cpp
Spell.h
SpellHandler.cpp
SpellMgr.cpp
SpellMgr.h
SQLStorages.cpp
SQLStorages.h
StateMgr.cpp
StateMgr.h
StateMgrImpl.h
StatSystem.cpp
TargetedMovementGenerator.cpp
TargetedMovementGenerator.h
TaxiHandler.cpp
TemporarySummon.cpp
TemporarySummon.h
ThreatManager.cpp
ThreatManager.h
TotemAI.cpp
TotemAI.h
Totem.cpp
Totem.h
TradeHandler.cpp
Transports.cpp
Transports.h
TransportSystem.cpp
TransportSystem.h
UnitAuraProcHandler.cpp
Unit.cpp
UnitEvents.h
Unit.h
UpdateData.cpp
UpdateData.h
UpdateFieldFlags.cpp
UpdateFieldFlags.h
UpdateFields.h
UpdateMask.h
Vehicle.cpp
Vehicle.h
VehicleHandler.cpp
VoiceChatHandler.cpp
WaypointManager.cpp
WaypointManager.h
WaypointMovementGenerator.cpp
WaypointMovementGenerator.h
Weather.cpp
Weather.h
World.cpp
World.h
WorldLocation.cpp
WorldLocation.h
WorldObjectEvents.cpp
WorldObjectEvents.h
WorldSession.cpp
WorldSession.h
WorldSocket.cpp
WorldSocket.h
WorldSocketMgr.cpp
WorldSocketMgr.h
WorldStateMgr.cpp
WorldStateMgr.h

AuctionHouseBot/AuctionHouseBot.cpp
AuctionHouseBot/AuctionHouseBot.h

BattleGround/BattleGroundAA.cpp
BattleGround/BattleGroundAA.h
BattleGround/BattleGroundAB.cpp
BattleGround/BattleGroundAB.h
BattleGround/BattleGroundAV.cpp
BattleGround/BattleGroundAV.h
BattleGround/BattleGroundBE.cpp
BattleGround/BattleGroundBE.h
BattleGround/BattleGround.cpp
BattleGround/BattleGroundDS.cpp
BattleGround/BattleGroundDS.h
BattleGround/BattleGroundEY.cpp
BattleGround/BattleGroundEY.h
BattleGround/BattleGround.h
BattleGround/BattleGroundHandler.cpp
BattleGround/BattleGroundIC.cpp
BattleGround/BattleGroundIC.h
BattleGround/BattleGroundMgr.cpp
BattleGround/BattleGroundMgr.h
BattleGround/BattleGroundNA.cpp
BattleGround/BattleGroundNA.h
BattleGround/BattleGroundRB.cpp
BattleGround/BattleGroundRB.h
BattleGround/BattleGroundRL.cpp
BattleGround/BattleGroundRL.h
BattleGround/BattleGroundRV.cpp
BattleGround/BattleGroundRV.h
BattleGround/BattleGroundSA.cpp
BattleGround/BattleGroundSA.h
BattleGround/BattleGroundWS.cpp
BattleGround/BattleGroundWS.h

OutdoorPvP/OutdoorPvP.cpp
OutdoorPvP/OutdoorPvPEP.cpp
OutdoorPvP/OutdoorPvPEP.h
OutdoorPvP/OutdoorPvPGH.cpp
OutdoorPvP/OutdoorPvPGH.h
OutdoorPvP/OutdoorPvP.h
OutdoorPvP/OutdoorPvPHP.cpp
OutdoorPvP/OutdoorPvPHP.h
OutdoorPvP/OutdoorPvPMgr.cpp
OutdoorPvP/OutdoorPvPMgr.h
OutdoorPvP/OutdoorPvPNA.cpp
OutdoorPvP/OutdoorPvPNA.h
OutdoorPvP/OutdoorPvPSI.cpp
OutdoorPvP/OutdoorPvPSI.h
OutdoorPvP/OutdoorPvPTF.cpp
OutdoorPvP/OutdoorPvPTF.h
OutdoorPvP/OutdoorPvPWG.cpp
OutdoorPvP/OutdoorPvPWG.h
OutdoorPvP/OutdoorPvPZM.cpp
OutdoorPvP/OutdoorPvPZM.h

movement/MoveSpline.cpp
movement/MoveSplineFlag.h
movement/MoveSpline.h
movement/MoveSplineInitArgs.h
movement/MoveSplineInit.cpp
movement/MoveSplineInit.h
movement/packet_builder.cpp
movement/packet_builder.h
movement/spline.cpp
movement/spline.h
movement/spline.impl.h
movement/typedefs.h
movement/util.cpp

vmap/BIH.cpp
vmap/BIH.h
vmap/BIHWrap.h
vmap/DynamicTree.cpp
vmap/DynamicTree.h
vmap/GameObjectModel.cpp
vmap/GameObjectModel.h
vmap/IVMapManager.h
vmap/MapTree.cpp
vmap/MapTree.h
vmap/ModelInstance.cpp
vmap/ModelInstance.h
vmap/RegularGrid.h
vmap/TileAssembler.cpp
vmap/TileAssembler.h
vmap/VMapDefinitions.h
vmap/VMapFactory.cpp
vmap/VMapFactory.h
vmap/VMapManager2.cpp
vmap/VMapManager2.h
vmap/VMapTools.h
vmap/WorldModel.cpp
vmap/WorldModel.h

warden/WardenBase.cpp
warden/WardenBase.h
warden/WardenDataStorage.cpp
warden/WardenDataStorage.h
warden/WardenMac.cpp
warden/WardenMac.h
warden/WardenModuleMac.h
warden/WardenModuleWin.h
warden/WardenWin.cpp
warden/WardenWin.h

playerbot/AiFactory.cpp
playerbot/AiFactory.h
playerbot/ChatFilter.cpp
playerbot/ChatFilter.h
playerbot/ChatHelper.cpp
playerbot/ChatHelper.h
playerbot/FleeManager.cpp
playerbot/FleeManager.h
playerbot/Helpers.cpp
playerbot/LazyCalculatedValue.h
playerbot/LootObjectStack.cpp
playerbot/LootObjectStack.h
playerbot/PlayerbotAI.cpp
playerbot/PlayerbotAI.h
playerbot/PlayerbotAIAware.h
playerbot/PlayerbotAIBase.cpp
playerbot/PlayerbotAIBase.h
playerbot/PlayerbotAIConfig.cpp
playerbot/PlayerbotAIConfig.h
playerbot/PlayerbotFactory.cpp
playerbot/PlayerbotFactory.h
playerbot/PlayerbotMgr.cpp
playerbot/PlayerbotMgr.h
playerbot/PlayerbotSecurity.cpp
playerbot/PlayerbotSecurity.h
playerbot/RandomPlayerbotFactory.cpp
playerbot/RandomPlayerbotFactory.h
playerbot/RandomPlayerbotMgr.cpp
playerbot/RandomPlayerbotMgr.h
playerbot/playerbot.h
playerbot/playerbotDefs.h
playerbot/strategy/Action.cpp
playerbot/strategy/Action.h
playerbot/strategy/ActionBasket.cpp
playerbot/strategy/ActionBasket.h
playerbot/strategy/AiObject.cpp
playerbot/strategy/AiObject.h
playerbot/strategy/AiObjectContext.cpp
playerbot/strategy/AiObjectContext.h
playerbot/strategy/Engine.cpp
playerbot/strategy/Engine.h
playerbot/strategy/Event.cpp
playerbot/strategy/Event.h
playerbot/strategy/ExternalEventHelper.h
playerbot/strategy/ItemVisitors.h
playerbot/strategy/Multiplier.cpp
playerbot/strategy/Multiplier.h
playerbot/strategy/NamedObjectContext.h
playerbot/strategy/PassiveMultiplier.cpp
playerbot/strategy/PassiveMultiplier.h
playerbot/strategy/Queue.cpp
playerbot/strategy/Queue.h
playerbot/strategy/Strategy.cpp
playerbot/strategy/Strategy.h
playerbot/strategy/StrategyContext.h
playerbot/strategy/Trigger.cpp
playerbot/strategy/Trigger.h
playerbot/strategy/Value.cpp
playerbot/strategy/Value.h
playerbot/strategy/actions/AcceptDuelAction.h
playerbot/strategy/actions/AcceptInvitationAction.h
playerbot/strategy/actions/AcceptQuestAction.cpp
playerbot/strategy/actions/AcceptQuestAction.h
playerbot/strategy/actions/AcceptResurrectAction.h
playerbot/strategy/actions/ActionContext.h
playerbot/strategy/actions/AddLootAction.cpp
playerbot/strategy/actions/AddLootAction.h
playerbot/strategy/actions/AreaTriggerAction.cpp
playerbot/strategy/actions/AreaTriggerAction.h
playerbot/strategy/actions/AttackAction.cpp
playerbot/strategy/actions/AttackAction.h
playerbot/strategy/actions/BankAction.cpp
playerbot/strategy/actions/BankAction.h
playerbot/strategy/actions/BuffAction.cpp
playerbot/strategy/actions/BuffAction.h
playerbot/strategy/actions/BuyAction.cpp
playerbot/strategy/actions/BuyAction.h
playerbot/strategy/actions/CastCustomSpellAction.cpp
playerbot/strategy/actions/CastCustomSpellAction.h
playerbot/strategy/actions/ChangeChatAction.cpp
playerbot/strategy/actions/ChangeChatAction.h
playerbot/strategy/actions/ChangeStrategyAction.cpp
playerbot/strategy/actions/ChangeStrategyAction.h
playerbot/strategy/actions/ChangeTalentsAction.cpp
playerbot/strategy/actions/ChangeTalentsAction.h
playerbot/strategy/actions/ChatActionContext.h
playerbot/strategy/actions/ChatShortcutActions.cpp
playerbot/strategy/actions/ChatShortcutActions.h
playerbot/strategy/actions/CheckMountStateAction.cpp
playerbot/strategy/actions/CheckMountStateAction.h
playerbot/strategy/actions/ChooseTargetActions.h
playerbot/strategy/actions/DestroyItemAction.cpp
playerbot/strategy/actions/DestroyItemAction.h
playerbot/strategy/actions/DropQuestAction.cpp
playerbot/strategy/actions/DropQuestAction.h
playerbot/strategy/actions/EmoteAction.cpp
playerbot/strategy/actions/EmoteAction.h
playerbot/strategy/actions/EquipAction.cpp
playerbot/strategy/actions/EquipAction.h
playerbot/strategy/actions/FollowActions.cpp
playerbot/strategy/actions/FollowActions.h
playerbot/strategy/actions/GenericActions.cpp
playerbot/strategy/actions/GenericActions.h
playerbot/strategy/actions/GenericSpellActions.cpp
playerbot/strategy/actions/GenericSpellActions.h
playerbot/strategy/actions/GossipHelloAction.cpp
playerbot/strategy/actions/GossipHelloAction.h
playerbot/strategy/actions/GuildBankAction.cpp
playerbot/strategy/actions/GuildBankAction.h
playerbot/strategy/actions/HelpAction.cpp
playerbot/strategy/actions/HelpAction.h
playerbot/strategy/actions/InventoryAction.cpp
playerbot/strategy/actions/InventoryAction.h
playerbot/strategy/actions/InventoryChangeFailureAction.cpp
playerbot/strategy/actions/InventoryChangeFailureAction.h
playerbot/strategy/actions/InviteToGroupAction.h
playerbot/strategy/actions/LeaveGroupAction.h
playerbot/strategy/actions/LfgActions.cpp
playerbot/strategy/actions/LfgActions.h
playerbot/strategy/actions/ListQuestsActions.cpp
playerbot/strategy/actions/ListQuestsActions.h
playerbot/strategy/actions/ListSpellsAction.cpp
playerbot/strategy/actions/ListSpellsAction.h
playerbot/strategy/actions/LogLevelAction.cpp
playerbot/strategy/actions/LogLevelAction.h
playerbot/strategy/actions/LootAction.cpp
playerbot/strategy/actions/LootAction.h
playerbot/strategy/actions/LootRollAction.cpp
playerbot/strategy/actions/LootRollAction.h
playerbot/strategy/actions/LootStrategyAction.cpp
playerbot/strategy/actions/LootStrategyAction.h
playerbot/strategy/actions/MovementActions.cpp
playerbot/strategy/actions/MovementActions.h
playerbot/strategy/actions/NonCombatActions.cpp
playerbot/strategy/actions/NonCombatActions.h
playerbot/strategy/actions/PassLeadershipToMasterAction.h
playerbot/strategy/actions/PositionAction.cpp
playerbot/strategy/actions/PositionAction.h
playerbot/strategy/actions/QueryItemUsageAction.cpp
playerbot/strategy/actions/QueryItemUsageAction.h
playerbot/strategy/actions/QueryQuestAction.cpp
playerbot/strategy/actions/QueryQuestAction.h
playerbot/strategy/actions/QuestAction.cpp
playerbot/strategy/actions/QuestAction.h
playerbot/strategy/actions/ReachTargetActions.h
playerbot/strategy/actions/ReadyCheckAction.cpp
playerbot/strategy/actions/ReadyCheckAction.h
playerbot/strategy/actions/ReleaseSpiritAction.h
playerbot/strategy/actions/RememberTaxiAction.cpp
playerbot/strategy/actions/RememberTaxiAction.h
playerbot/strategy/actions/RepairAllAction.cpp
playerbot/strategy/actions/RepairAllAction.h
playerbot/strategy/actions/ResetAiAction.cpp
playerbot/strategy/actions/ResetAiAction.h
playerbot/strategy/actions/ReviveFromCorpseAction.cpp
playerbot/strategy/actions/ReviveFromCorpseAction.h
playerbot/strategy/actions/RewardAction.cpp
playerbot/strategy/actions/RewardAction.h
playerbot/strategy/actions/RtiAction.h
playerbot/strategy/actions/SellAction.cpp
playerbot/strategy/actions/SellAction.h
playerbot/strategy/actions/SetHomeAction.cpp
playerbot/strategy/actions/SetHomeAction.h
playerbot/strategy/actions/StatsAction.cpp
playerbot/strategy/actions/StatsAction.h
playerbot/strategy/actions/StayActions.cpp
playerbot/strategy/actions/StayActions.h
playerbot/strategy/actions/SuggestWhatToDoAction.cpp
playerbot/strategy/actions/SuggestWhatToDoAction.h
playerbot/strategy/actions/TalkToQuestGiverAction.cpp
playerbot/strategy/actions/TalkToQuestGiverAction.h
playerbot/strategy/actions/TaxiAction.cpp
playerbot/strategy/actions/TaxiAction.h
playerbot/strategy/actions/TeleportAction.cpp
playerbot/strategy/actions/TeleportAction.h
playerbot/strategy/actions/TellCastFailedAction.cpp
playerbot/strategy/actions/TellCastFailedAction.h
playerbot/strategy/actions/TellItemCountAction.cpp
playerbot/strategy/actions/TellItemCountAction.h
playerbot/strategy/actions/TellLosAction.cpp
playerbot/strategy/actions/TellLosAction.h
playerbot/strategy/actions/TellMasterAction.h
playerbot/strategy/actions/TellReputationAction.cpp
playerbot/strategy/actions/TellReputationAction.h
playerbot/strategy/actions/TellTargetAction.cpp
playerbot/strategy/actions/TellTargetAction.h
playerbot/strategy/actions/TradeAction.cpp
playerbot/strategy/actions/TradeAction.h
playerbot/strategy/actions/TradeStatusAction.cpp
playerbot/strategy/actions/TradeStatusAction.h
playerbot/strategy/actions/TrainerAction.cpp
playerbot/strategy/actions/TrainerAction.h
playerbot/strategy/actions/UnequipAction.cpp
playerbot/strategy/actions/UnequipAction.h
playerbot/strategy/actions/UseItemAction.cpp
playerbot/strategy/actions/UseItemAction.h
playerbot/strategy/actions/UseMeetingStoneAction.cpp
playerbot/strategy/actions/UseMeetingStoneAction.h
playerbot/strategy/actions/WhoAction.cpp
playerbot/strategy/actions/WhoAction.h
playerbot/strategy/actions/WorldPacketActionContext.h
playerbot/strategy/druid/BearTankDruidStrategy.cpp
playerbot/strategy/druid/BearTankDruidStrategy.h
playerbot/strategy/druid/CasterDruidStrategy.cpp
playerbot/strategy/druid/CasterDruidStrategy.h
playerbot/strategy/druid/CatDpsDruidStrategy.cpp
playerbot/strategy/druid/CatDpsDruidStrategy.h
playerbot/strategy/druid/DruidActions.cpp
playerbot/strategy/druid/DruidActions.h
playerbot/strategy/druid/DruidAiObjectContext.cpp
playerbot/strategy/druid/DruidAiObjectContext.h
playerbot/strategy/druid/DruidBearActions.h
playerbot/strategy/druid/DruidCatActions.h
playerbot/strategy/druid/DruidMultipliers.cpp
playerbot/strategy/druid/DruidMultipliers.h
playerbot/strategy/druid/DruidShapeshiftActions.h
playerbot/strategy/druid/DruidTriggers.cpp
playerbot/strategy/druid/DruidTriggers.h
playerbot/strategy/druid/FeralDruidStrategy.cpp
playerbot/strategy/druid/FeralDruidStrategy.h
playerbot/strategy/druid/GenericDruidNonCombatStrategy.cpp
playerbot/strategy/druid/GenericDruidNonCombatStrategy.h
playerbot/strategy/druid/GenericDruidStrategy.cpp
playerbot/strategy/druid/GenericDruidStrategy.h
playerbot/strategy/druid/HealDruidStrategy.cpp
playerbot/strategy/druid/HealDruidStrategy.h
playerbot/strategy/generic/AttackEnemyPlayersStrategy.cpp
playerbot/strategy/generic/AttackEnemyPlayersStrategy.h
playerbot/strategy/generic/AttackRtiStrategy.cpp
playerbot/strategy/generic/AttackRtiStrategy.h
playerbot/strategy/generic/AttackWeakStrategy.cpp
playerbot/strategy/generic/AttackWeakStrategy.h
playerbot/strategy/generic/CastTimeStrategy.cpp
playerbot/strategy/generic/CastTimeStrategy.h
playerbot/strategy/generic/ChatCommandHandlerStrategy.cpp
playerbot/strategy/generic/ChatCommandHandlerStrategy.h
playerbot/strategy/generic/CombatStrategy.cpp
playerbot/strategy/generic/CombatStrategy.h
playerbot/strategy/generic/ConserveManaStrategy.cpp
playerbot/strategy/generic/ConserveManaStrategy.h
playerbot/strategy/generic/DeadStrategy.cpp
playerbot/strategy/generic/DeadStrategy.h
playerbot/strategy/generic/DpsAoeStrategy.cpp
playerbot/strategy/generic/DpsAoeStrategy.h
playerbot/strategy/generic/DpsAssistStrategy.cpp
playerbot/strategy/generic/DpsAssistStrategy.h
playerbot/strategy/generic/DuelStrategy.cpp
playerbot/strategy/generic/DuelStrategy.h
playerbot/strategy/generic/EmoteStrategy.cpp
playerbot/strategy/generic/EmoteStrategy.h
playerbot/strategy/generic/FleeStrategy.cpp
playerbot/strategy/generic/FleeStrategy.h
playerbot/strategy/generic/FollowLineStrategy.cpp
playerbot/strategy/generic/FollowLineStrategy.h
playerbot/strategy/generic/FollowMasterRandomStrategy.cpp
playerbot/strategy/generic/FollowMasterRandomStrategy.h
playerbot/strategy/generic/FollowMasterStrategy.cpp
playerbot/strategy/generic/FollowMasterStrategy.h
playerbot/strategy/generic/GrindingStrategy.cpp
playerbot/strategy/generic/GrindingStrategy.h
playerbot/strategy/generic/GuardStrategy.cpp
playerbot/strategy/generic/GuardStrategy.h
playerbot/strategy/generic/KiteStrategy.cpp
playerbot/strategy/generic/KiteStrategy.h
playerbot/strategy/generic/LootNonCombatStrategy.cpp
playerbot/strategy/generic/LootNonCombatStrategy.h
playerbot/strategy/generic/MeleeCombatStrategy.cpp
playerbot/strategy/generic/MeleeCombatStrategy.h
playerbot/strategy/generic/NonCombatStrategy.cpp
playerbot/strategy/generic/NonCombatStrategy.h
playerbot/strategy/generic/PassTroughStrategy.h
playerbot/strategy/generic/PassiveStrategy.cpp
playerbot/strategy/generic/PassiveStrategy.h
playerbot/strategy/generic/PullStrategy.cpp
playerbot/strategy/generic/PullStrategy.h
playerbot/strategy/generic/QuestStrategies.cpp
playerbot/strategy/generic/QuestStrategies.h
playerbot/strategy/generic/RacialsStrategy.cpp
playerbot/strategy/generic/RacialsStrategy.h
playerbot/strategy/generic/RangedCombatStrategy.cpp
playerbot/strategy/generic/RangedCombatStrategy.h
playerbot/strategy/generic/RunawayStrategy.cpp
playerbot/strategy/generic/RunawayStrategy.h
playerbot/strategy/generic/StayCircleStrategy.cpp
playerbot/strategy/generic/StayCircleStrategy.h
playerbot/strategy/generic/StayCombatStrategy.cpp
playerbot/strategy/generic/StayCombatStrategy.h
playerbot/strategy/generic/StayLineStrategy.cpp
playerbot/strategy/generic/StayLineStrategy.h
playerbot/strategy/generic/StayStrategy.cpp
playerbot/strategy/generic/StayStrategy.h
playerbot/strategy/generic/TankAoeStrategy.cpp
playerbot/strategy/generic/TankAoeStrategy.h
playerbot/strategy/generic/TankAssistStrategy.cpp
playerbot/strategy/generic/TankAssistStrategy.h
playerbot/strategy/generic/TellTargetStrategy.cpp
playerbot/strategy/generic/TellTargetStrategy.h
playerbot/strategy/generic/ThreatStrategy.cpp
playerbot/strategy/generic/ThreatStrategy.h
playerbot/strategy/generic/UseFoodStrategy.cpp
playerbot/strategy/generic/UseFoodStrategy.h
playerbot/strategy/generic/UsePotionsStrategy.cpp
playerbot/strategy/generic/UsePotionsStrategy.h
playerbot/strategy/generic/WorldPacketHandlerStrategy.cpp
playerbot/strategy/generic/WorldPacketHandlerStrategy.h
playerbot/strategy/hunter/DpsHunterStrategy.cpp
playerbot/strategy/hunter/DpsHunterStrategy.h
playerbot/strategy/hunter/GenericHunterNonCombatStrategy.cpp
playerbot/strategy/hunter/GenericHunterNonCombatStrategy.h
playerbot/strategy/hunter/GenericHunterStrategy.cpp
playerbot/strategy/hunter/GenericHunterStrategy.h
playerbot/strategy/hunter/HunterActions.cpp
playerbot/strategy/hunter/HunterActions.h
playerbot/strategy/hunter/HunterAiObjectContext.cpp
playerbot/strategy/hunter/HunterAiObjectContext.h
playerbot/strategy/hunter/HunterBuffStrategies.cpp
playerbot/strategy/hunter/HunterBuffStrategies.h
playerbot/strategy/hunter/HunterMultipliers.cpp
playerbot/strategy/hunter/HunterMultipliers.h
playerbot/strategy/hunter/HunterTriggers.cpp
playerbot/strategy/hunter/HunterTriggers.h
playerbot/strategy/mage/ArcaneMageStrategy.cpp
playerbot/strategy/mage/ArcaneMageStrategy.h
playerbot/strategy/mage/FireMageStrategy.cpp
playerbot/strategy/mage/FireMageStrategy.h
playerbot/strategy/mage/FrostMageStrategy.cpp
playerbot/strategy/mage/FrostMageStrategy.h
playerbot/strategy/mage/GenericMageNonCombatStrategy.cpp
playerbot/strategy/mage/GenericMageNonCombatStrategy.h
playerbot/strategy/mage/GenericMageStrategy.cpp
playerbot/strategy/mage/GenericMageStrategy.h
playerbot/strategy/mage/MageActions.cpp
playerbot/strategy/mage/MageActions.h
playerbot/strategy/mage/MageAiObjectContext.cpp
playerbot/strategy/mage/MageAiObjectContext.h
playerbot/strategy/mage/MageMultipliers.cpp
playerbot/strategy/mage/MageMultipliers.h
playerbot/strategy/mage/MageTriggers.cpp
playerbot/strategy/mage/MageTriggers.h
playerbot/strategy/paladin/DpsPaladinStrategy.cpp
playerbot/strategy/paladin/DpsPaladinStrategy.h
playerbot/strategy/paladin/GenericPaladinNonCombatStrategy.cpp
playerbot/strategy/paladin/GenericPaladinNonCombatStrategy.h
playerbot/strategy/paladin/GenericPaladinStrategy.cpp
playerbot/strategy/paladin/GenericPaladinStrategy.h
playerbot/strategy/paladin/GenericPaladinStrategyActionNodeFactory.h
playerbot/strategy/paladin/PaladinActions.cpp
playerbot/strategy/paladin/PaladinActions.h
playerbot/strategy/paladin/PaladinAiObjectContext.cpp
playerbot/strategy/paladin/PaladinAiObjectContext.h
playerbot/strategy/paladin/PaladinBuffStrategies.cpp
playerbot/strategy/paladin/PaladinBuffStrategies.h
playerbot/strategy/paladin/PaladinMultipliers.cpp
playerbot/strategy/paladin/PaladinMultipliers.h
playerbot/strategy/paladin/PaladinTriggers.cpp
playerbot/strategy/paladin/PaladinTriggers.h
playerbot/strategy/paladin/TankPaladinStrategy.cpp
playerbot/strategy/paladin/TankPaladinStrategy.h
playerbot/strategy/priest/GenericPriestStrategy.cpp
playerbot/strategy/priest/GenericPriestStrategy.h
playerbot/strategy/priest/GenericPriestStrategyActionNodeFactory.h
playerbot/strategy/priest/HealPriestStrategy.cpp
playerbot/strategy/priest/HealPriestStrategy.h
playerbot/strategy/priest/HolyPriestStrategy.cpp
playerbot/strategy/priest/HolyPriestStrategy.h
playerbot/strategy/priest/PriestActions.cpp
playerbot/strategy/priest/PriestActions.h
playerbot/strategy/priest/PriestAiObjectContext.cpp
playerbot/strategy/priest/PriestAiObjectContext.h
playerbot/strategy/priest/PriestMultipliers.cpp
playerbot/strategy/priest/PriestMultipliers.h
playerbot/strategy/priest/PriestNonCombatStrategy.cpp
playerbot/strategy/priest/PriestNonCombatStrategy.h
playerbot/strategy/priest/PriestNonCombatStrategyActionNodeFactory.h
playerbot/strategy/priest/PriestTriggers.cpp
playerbot/strategy/priest/PriestTriggers.h
playerbot/strategy/priest/ShadowPriestStrategy.cpp
playerbot/strategy/priest/ShadowPriestStrategy.h
playerbot/strategy/priest/ShadowPriestStrategyActionNodeFactory.h
playerbot/strategy/rogue/DpsRogueStrategy.cpp
playerbot/strategy/rogue/DpsRogueStrategy.h
playerbot/strategy/rogue/GenericRogueNonCombatStrategy.cpp
playerbot/strategy/rogue/GenericRogueNonCombatStrategy.h
playerbot/strategy/rogue/RogueActions.cpp
playerbot/strategy/rogue/RogueActions.h
playerbot/strategy/rogue/RogueAiObjectContext.cpp
playerbot/strategy/rogue/RogueAiObjectContext.h
playerbot/strategy/rogue/RogueComboActions.h
playerbot/strategy/rogue/RogueFinishingActions.h
playerbot/strategy/rogue/RogueMultipliers.cpp
playerbot/strategy/rogue/RogueMultipliers.h
playerbot/strategy/rogue/RogueOpeningActions.h
playerbot/strategy/rogue/RogueTriggers.cpp
playerbot/strategy/rogue/RogueTriggers.h
playerbot/strategy/shaman/CasterShamanStrategy.cpp
playerbot/strategy/shaman/CasterShamanStrategy.h
playerbot/strategy/shaman/GenericShamanStrategy.cpp
playerbot/strategy/shaman/GenericShamanStrategy.h
playerbot/strategy/shaman/HealShamanStrategy.cpp
playerbot/strategy/shaman/HealShamanStrategy.h
playerbot/strategy/shaman/MeleeShamanStrategy.cpp
playerbot/strategy/shaman/MeleeShamanStrategy.h
playerbot/strategy/shaman/ShamanActions.cpp
playerbot/strategy/shaman/ShamanActions.h
playerbot/strategy/shaman/ShamanAiObjectContext.cpp
playerbot/strategy/shaman/ShamanAiObjectContext.h
playerbot/strategy/shaman/ShamanMultipliers.cpp
playerbot/strategy/shaman/ShamanMultipliers.h
playerbot/strategy/shaman/ShamanNonCombatStrategy.cpp
playerbot/strategy/shaman/ShamanNonCombatStrategy.h
playerbot/strategy/shaman/ShamanTriggers.cpp
playerbot/strategy/shaman/ShamanTriggers.h
playerbot/strategy/shaman/TotemsShamanStrategy.cpp
playerbot/strategy/shaman/TotemsShamanStrategy.h
playerbot/strategy/triggers/ChatCommandTrigger.h
playerbot/strategy/triggers/ChatTriggerContext.h
playerbot/strategy/triggers/CureTriggers.cpp
playerbot/strategy/triggers/CureTriggers.h
playerbot/strategy/triggers/GenericTriggers.cpp
playerbot/strategy/triggers/GenericTriggers.h
playerbot/strategy/triggers/HealthTriggers.cpp
playerbot/strategy/triggers/HealthTriggers.h
playerbot/strategy/triggers/LootTriggers.cpp
playerbot/strategy/triggers/LootTriggers.h
playerbot/strategy/triggers/RangeTriggers.h
playerbot/strategy/triggers/TriggerContext.h
playerbot/strategy/triggers/WithinAreaTrigger.h
playerbot/strategy/triggers/WorldPacketTrigger.h
playerbot/strategy/triggers/WorldPacketTriggerContext.h
playerbot/strategy/values/AlwaysLootListValue.h
playerbot/strategy/values/AoeHealValues.cpp
playerbot/strategy/values/AoeHealValues.h
playerbot/strategy/values/AttackerCountValues.cpp
playerbot/strategy/values/AttackerCountValues.h
playerbot/strategy/values/AttackerWithoutAuraTargetValue.cpp
playerbot/strategy/values/AttackerWithoutAuraTargetValue.h
playerbot/strategy/values/AttackersValue.cpp
playerbot/strategy/values/AttackersValue.h
playerbot/strategy/values/AvailableLootValue.h
playerbot/strategy/values/CcTargetValue.cpp
playerbot/strategy/values/CcTargetValue.h
playerbot/strategy/values/ChatValue.h
playerbot/strategy/values/CurrentCcTargetValue.cpp
playerbot/strategy/values/CurrentCcTargetValue.h
playerbot/strategy/values/CurrentTargetValue.cpp
playerbot/strategy/values/CurrentTargetValue.h
playerbot/strategy/values/DistanceValue.h
playerbot/strategy/values/DpsTargetValue.cpp
playerbot/strategy/values/DpsTargetValue.h
playerbot/strategy/values/DuelTargetValue.cpp
playerbot/strategy/values/DuelTargetValue.h
playerbot/strategy/values/EnemyPlayerValue.cpp
playerbot/strategy/values/EnemyPlayerValue.h
playerbot/strategy/values/GrindTargetValue.cpp
playerbot/strategy/values/GrindTargetValue.h
playerbot/strategy/values/HasAvailableLootValue.h
playerbot/strategy/values/HasTotemValue.h
playerbot/strategy/values/InvalidTargetValue.cpp
playerbot/strategy/values/InvalidTargetValue.h
playerbot/strategy/values/IsBehindValue.h
playerbot/strategy/values/IsFacingValue.h
playerbot/strategy/values/IsMovingValue.h
playerbot/strategy/values/ItemCountValue.cpp
playerbot/strategy/values/ItemCountValue.h
playerbot/strategy/values/ItemForSpellValue.cpp
playerbot/strategy/values/ItemForSpellValue.h
playerbot/strategy/values/LastMovementValue.h
playerbot/strategy/values/LastSpellCastValue.h
playerbot/strategy/values/LeastHpTargetValue.cpp
playerbot/strategy/values/LeastHpTargetValue.h
playerbot/strategy/values/LineTargetValue.cpp
playerbot/strategy/values/LineTargetValue.h
playerbot/strategy/values/LogLevelValue.h
playerbot/strategy/values/LootStrategyValue.h
playerbot/strategy/values/MasterTargetValue.h
playerbot/strategy/values/NearestAdsValue.cpp
playerbot/strategy/values/NearestAdsValue.h
playerbot/strategy/values/NearestCorpsesValue.cpp
playerbot/strategy/values/NearestCorpsesValue.h
playerbot/strategy/values/NearestGameObjects.cpp
playerbot/strategy/values/NearestGameObjects.h
playerbot/strategy/values/NearestNpcsValue.cpp
playerbot/strategy/values/NearestNpcsValue.h
playerbot/strategy/values/NearestUnitsValue.h
playerbot/strategy/values/PartyMemberToDispel.cpp
playerbot/strategy/values/PartyMemberToDispel.h
playerbot/strategy/values/PartyMemberToHeal.cpp
playerbot/strategy/values/PartyMemberToHeal.h
playerbot/strategy/values/PartyMemberToResurrect.cpp
playerbot/strategy/values/PartyMemberToResurrect.h
playerbot/strategy/values/PartyMemberValue.cpp
playerbot/strategy/values/PartyMemberValue.h
playerbot/strategy/values/PartyMemberWithoutAuraValue.cpp
playerbot/strategy/values/PartyMemberWithoutAuraValue.h
playerbot/strategy/values/PetTargetValue.h
playerbot/strategy/values/PositionValue.cpp
playerbot/strategy/values/PositionValue.h
playerbot/strategy/values/PossibleTargetsValue.cpp
playerbot/strategy/values/PossibleTargetsValue.h
playerbot/strategy/values/RtiTargetValue.h
playerbot/strategy/values/RtiValue.cpp
playerbot/strategy/values/RtiValue.h
playerbot/strategy/values/SelfTargetValue.h
playerbot/strategy/values/SpellCastUsefulValue.cpp
playerbot/strategy/values/SpellCastUsefulValue.h
playerbot/strategy/values/SpellIdValue.cpp
playerbot/strategy/values/SpellIdValue.h
playerbot/strategy/values/StatsValues.cpp
playerbot/strategy/values/StatsValues.h
playerbot/strategy/values/TankTargetValue.cpp
playerbot/strategy/values/TankTargetValue.h
playerbot/strategy/values/TargetValue.cpp
playerbot/strategy/values/TargetValue.h
playerbot/strategy/values/ThreatValues.cpp
playerbot/strategy/values/ThreatValues.h
playerbot/strategy/values/ValueContext.h
playerbot/strategy/warlock/DpsWarlockStrategy.cpp
playerbot/strategy/warlock/DpsWarlockStrategy.h
playerbot/strategy/warlock/GenericWarlockNonCombatStrategy.cpp
playerbot/strategy/warlock/GenericWarlockNonCombatStrategy.h
playerbot/strategy/warlock/GenericWarlockStrategy.cpp
playerbot/strategy/warlock/GenericWarlockStrategy.h
playerbot/strategy/warlock/TankWarlockStrategy.cpp
playerbot/strategy/warlock/TankWarlockStrategy.h
playerbot/strategy/warlock/WarlockActions.cpp
playerbot/strategy/warlock/WarlockActions.h
playerbot/strategy/warlock/WarlockAiObjectContext.cpp
playerbot/strategy/warlock/WarlockAiObjectContext.h
playerbot/strategy/warlock/WarlockMultipliers.cpp
playerbot/strategy/warlock/WarlockMultipliers.h
playerbot/strategy/warlock/WarlockTriggers.cpp
playerbot/strategy/warlock/WarlockTriggers.h
playerbot/strategy/warrior/DpsWarriorStrategy.cpp
playerbot/strategy/warrior/DpsWarriorStrategy.h
playerbot/strategy/warrior/GenericWarriorNonCombatStrategy.cpp
playerbot/strategy/warrior/GenericWarriorNonCombatStrategy.h
playerbot/strategy/warrior/GenericWarriorStrategy.cpp
playerbot/strategy/warrior/GenericWarriorStrategy.h
playerbot/strategy/warrior/TankWarriorStrategy.cpp
playerbot/strategy/warrior/TankWarriorStrategy.h
playerbot/strategy/warrior/WarriorActions.cpp
playerbot/strategy/warrior/WarriorActions.h
playerbot/strategy/warrior/WarriorAiObjectContext.cpp
playerbot/strategy/warrior/WarriorAiObjectContext.h
playerbot/strategy/warrior/WarriorMultipliers.cpp
playerbot/strategy/warrior/WarriorMultipliers.h
playerbot/strategy/warrior/WarriorTriggers.cpp
playerbot/strategy/warrior/WarriorTriggers.h

ahbot/AhBot.cpp
ahbot/AhBot.h
ahbot/AhBotConfig.cpp
ahbot/AhBotConfig.h
ahbot/Category.cpp
ahbot/Category.h
ahbot/ConsumableCategory.cpp
ahbot/ConsumableCategory.h
ahbot/ItemBag.cpp
ahbot/ItemBag.h
ahbot/PricingStrategy.cpp
ahbot/PricingStrategy.h
ahbot/TradeCategory.cpp
ahbot/TradeCategory.h

)

include_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}
  ${CMAKE_CURRENT_SOURCE_DIR}/vmap
  ${CMAKE_CURRENT_SOURCE_DIR}/playerbot
  ${CMAKE_CURRENT_SOURCE_DIR}/AuctionHouseBot
  ${CMAKE_CURRENT_SOURCE_DIR}/warden
  ${CMAKE_CURRENT_SOURCE_DIR}/OutdoorPvP
  ${CMAKE_CURRENT_SOURCE_DIR}/BattleGround
  ${CMAKE_SOURCE_DIR}/dep/include/g3dlite
  ${CMAKE_SOURCE_DIR}/dep/recastnavigation/Detour
  ${CMAKE_SOURCE_DIR}/dep/recastnavigation/
  ${CMAKE_SOURCE_DIR}/dep/include
  ${CMAKE_SOURCE_DIR}/src/shared
  ${CMAKE_SOURCE_DIR}/src/framework
  ${CMAKE_BINARY_DIR}
  ${CMAKE_BINARY_DIR}/src/shared
  ${MYSQL_INCLUDE_DIR}
  ${ACE_INCLUDE_DIR}
)

source_group("Object"
  REGULAR_EXPRESSION .*
)

source_group("World/Handlers"
  # REGULAR_EXPRESSION Mgr|Handler|Manager|BattleGround|Cell|Channel|Chat|Gossip|Grid|Group|Instance|Mail|Map|Path|Pool|Quest|Script|Skill|Spell|Transports|Update|Weather|World
  REGULAR_EXPRESSION Mgr|Handler|Manager|Cell|Channel|Chat|Gossip|Grid|Instance|Map|Path|Pool|Script|Skill|Transports|Update|Weather|World
)

source_group("Motion generators"
  REGULAR_EXPRESSION MoveMap|MoveMapSharedDefines|Generator|MotionMaster
)

source_group("Server"
  REGULAR_EXPRESSION Socket|Session|Opcodes|DBC
  FILES
    SharedDefines.h
)

source_group("Chat Commands"
  REGULAR_EXPRESSION Level[0-9]
  FILES
    debugcmds.cpp
)

source_group("Tool"
  REGULAR_EXPRESSION DatabaseCleaner|Language|PlayerDump
)

source_group("References"
  REGULAR_EXPRESSION Reference|RefManager|ThreatManager
)

source_group("Movement"
  REGULAR_EXPRESSION spline|Spline|packet_builder
  FILES
    movement/typedefs.h
    movement/util.cpp
)

source_group("AhBot"
  REGULAR_EXPRESSION ahbot/.*
)

source_group("playerbot"
  REGULAR_EXPRESSION playerbot/.*
)

source_group("playerbot_strategy"
  REGULAR_EXPRESSION playerbot/strategy/.*
)

source_group("playerbot_strategy_actions"
  REGULAR_EXPRESSION playerbot/strategy/actions/.*
)

source_group("playerbot_strategy_triggers"
  REGULAR_EXPRESSION playerbot/strategy/triggers/.*
)

source_group("playerbot_strategy_values"
  REGULAR_EXPRESSION playerbot/strategy/values/.*
)

source_group("playerbot_strategy_druid"
  REGULAR_EXPRESSION playerbot/strategy/druid/.*
)
source_group("playerbot_strategy_hunter"
  REGULAR_EXPRESSION playerbot/strategy/hunter/.*
)
source_group("playerbot_strategy_mage"
  REGULAR_EXPRESSION playerbot/strategy/mage/.*
)
source_group("playerbot_strategy_paladin"
  REGULAR_EXPRESSION playerbot/strategy/paladin/.*
)
source_group("playerbot_strategy_priest"
  REGULAR_EXPRESSION playerbot/strategy/priest/.*
)
source_group("playerbot_strategy_rogue"
  REGULAR_EXPRESSION playerbot/strategy/rogue/.*
)
source_group("playerbot_strategy_shaman"
  REGULAR_EXPRESSION playerbot/strategy/shaman/.*
)
source_group("playerbot_strategy_warlock"
  REGULAR_EXPRESSION playerbot/strategy/warlock/.*
)
source_group("playerbot_strategy_warrior"
  REGULAR_EXPRESSION playerbot/strategy/warrior/.*
)

if(PCH)
  include_directories(${CMAKE_CURRENT_BINARY_DIR})
endif()

add_library(${LIBRARY_NAME} STATIC
  ${LIBRARY_SRCS}
)

target_link_libraries(${LIBRARY_NAME}
  shared
  detour
)

if(UNIX)
  # Both systems don't have libdl and don't need them
  if (NOT (CMAKE_SYSTEM_NAME STREQUAL "FreeBSD" OR CMAKE_SYSTEM_NAME STREQUAL "NetBSD"))
    target_link_libraries(${LIBRARY_NAME}
      dl
    )
  endif()
endif()

add_dependencies(${LIBRARY_NAME} revision.h)
if(NOT ACE_USE_EXTERNAL)
  add_dependencies(${LIBRARY_NAME} ACE_Project)
endif()

# Generate precompiled header
if(PCH)
  if(MSVC OR XCODE)
    if(MSVC)
      set(game_pch "${CMAKE_CURRENT_SOURCE_DIR}/pchdef.cpp")
    endif()
    add_native_precompiled_header(${LIBRARY_NAME} ${CMAKE_CURRENT_SOURCE_DIR}/pchdef.h)
  elseif(CMAKE_COMPILER_IS_GNUCXX)
    add_precompiled_header(${LIBRARY_NAME} ${CMAKE_CURRENT_SOURCE_DIR}/pchdef.h)
    if(NOT ACE_USE_EXTERNAL)
      add_dependencies(game_pch_dephelp ACE_Project)
    endif()
  endif()
endif()
