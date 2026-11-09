# Update history (in descending order)

## U6 - 2026-10-18
1. Removed unused sections in national focuses so they will show completion effects
2. "Align Hungary/Romania" focuses can no longer be taken when at war with them as in 1.6 patch
3. Replaced puppet effect in events with set_autonomy to avoid crashes
4. Execute nuclear strikes on Japan mission will no longer claim it will fail when it will, in fact, succeed
5. Italy will no longer try to join Japan's faction on historical focus
6. Tweaked tooltips in "Demand Indochina" decision to make more sense
7. Fixed typo in cavalry officer description
8. Fixed several historically incorrect city/state names for the USSR
9. Added Viriatos to Portugal so they can send volunteers to Spain in the civil war
10. Numerous small tweaks across the board

## U5.2 - 2025-12-07
1. Battle royale hotfix

## U5.1 - 2025-12-04
1. Localisation file error hotfix

## U5 - 2025-12-04
1. Numerous changes to national focuses, decisions, events and AI behavior (credit: Paradox Interactive, Mefisto1029)
2. Added battle royale test decision

## U4 - 2025-10-28
1. Made CHI_political_power_struggle only visible when there's at least one Chinese state still existing and is independent
2. Removed censorship from support equipment icon
3. Tweaked GER focuses for AI to be less dumb at war
4. Removed mention of national unity which is no longer in the game in ger_sov_buddies_tooltip:0
5. Fixed an issue where the Soviet Union would retain a claim on Petsamo after the peacedeal in the Winter War leading to a second war within a short time as in 1.6 patch
6. Numerous AI tweaks
7. Fixed typo in germany.104.a
8. Fixed missing icon in USA_homeland_defense
9. The Comintern influence idea now will be removed if the USSR doesn't exists, is subject or no longer communist
10. Replaced puppet effect with set_autonomy to stop the game from crashing
11. Fixed DOD_hungary.92.e and wtt_germany.65.b having ai_chance of factor = 0 used with modifiers
12. Minor fixes to PRC events (credit: Mefisto1029)
13. German Plan Z mission will no longer claim it will fail when it will, in fact, succeed as in 1.6 patch
14. Added a decision to remove SS division locks
15. Added a decision to remove democratic party lock from form EU decision for minor European nations

## U3 - 2025-05-29
1. Austria cannot be annexed by Hungary via NF anymore if it is at war (source: bitmode)
2. ITA's Fortification Effort now grants coastal bunker on province 6891 instead of 9863 (source: ansh666)
3. Should FRA dismantle the Maginot Line using special projects decision, the idea "Protected by the Maginot Line" gets removed to prevent FRA being stuck forever with it
4. The U.S. influence and protection ideas now will be removed if the USA doesn't exists or is a puppet of another country
5. Refinery concern's cost is decreased from 300 to 250 political power for the sake of consistency to other high cost ideas
6. Prevented AI PRC from joining the Comintern right away and thus receiving an unfair advantage against CHI in the civil war
7. The Repair Suez/Panama Canal will no longer pop up if you actually don't control the states required to take the decisions
8. Made CHI_industrial_evacuations decision category only visible when at war
9. ROM's Carol II idea now will be removed if ROM is a puppet of another country (source: Equilibrius)
10. Minor changes to colonial division templates in 1936 French OOB (source: James Hale)
11. The Manchukuo focus Assertiveness also will be bypassed if Japan has a civil war to avoid breaking its focus tree
12. Fixed typo in REASSIGN_FULL_ORDERS_GROUP_TEXT
13. AIRWING_MISSION_SET_REINF_LIMIT_RCLICK now properly says that you need to left mouse click instead of right mouse click (source: bitmode)
14. Fixed mismatched localization string wtt_soviet_hold_city_o_success in wtt_soviet_hold_city events (source: bitmode)
15. Fixed localization error in DOD_yugoslavia.20.t (source: bitmode)
16. Stop Iceland from uncapitulating itself if occupied already as in 1.11 patch
17. Added checks to Hungarian focus "Renew the Rome Protocols" to make sure Austria and Italy exist and are independent as in 1.12.12 patch
18. POL now will choose germany.86.b (Danzig will remain Gdansk!) more frequently if it is in faction with a major country (source: Warden2054)
19. tfv_australia.11 no longer causes CTD (NEEDS A PROPER FIX. As of now the original puppet effect, which causes a crash, is changed to annex_country instead. Said to be fixed in MtG; however, I haven't found any confirmation on that. Source: ElectricWolf).
20. Fixed Ljubljana Award transferring an island in the Indian Ocean instead of Greece's Central Macedonia as in 1.6 patch
21. Added 5 admirals to each country except majors to compensate for the fact that newly-generated admirals can not gain traits (NEEDS A PROPER FIX. The cause of the issue is unknown and I haven't found any confirmation that it has been fixed. Source: DeValiere)
22. Fixed l10n error in DR_IDEOLOGICAL_ACCEPTANCE:1 (source: bitmode)
23. Fixed a trigger in election events that had the date reversed as in 1.6.1 patch

## U2.1 - 2025-05-09
1. Israel and Palestine now have correct capital ID (source: Risuman)
2. Italy now can skip national focus Triumph in Africa if Ethiopia managed to take control of Eritrea and Somalia
3. Icelandic independence event now will fire only once
4. The idea GER_preparing_ITA_coup is now required for GER to be able to assassinate Benito Mussolini (source: bitmode)
5. Country flags YUG_GER_pressure_1 and YUG_GER_pressure_2 now have an impact on YUG's AI by increasing a chance that it will pick YUG_invite_german_military_mission over YUG_non_discriminating_officer_promotions (source: bitmode)
6. Refinery concerns are now providing +10% research speed bonus to all technologies in the Industry research tab like the industry concern, but the cost is increased to 300 political power to balance (source: Neciota)
7. Hungary no longer can demand a referendum if Austria doesn't exists (source: Oneknown)
8. Rocket sites now produces 5 rockets as intended instead of 1 (source: bitmode)
9. Removed Carrier Naval Bomber 1 from 1936 Sweden start as it neither has appropriate tech nor it is historical (source: bitmode)
10. MacDonald's Proposal now requires ENG to be at peace with IRE to fire (source: Darrman)
11. china.14 now correctly clears border war status from states 744, 607 and 622 instead of 605, 607, 620 and 622 (source: bitmode)
12. Ironside admiral trait now correctly checks for XP gain conditions (source: cnwi)
13. Hungary's Reclaim the Empire focus no longer blocked by controlling any of the states required (source: bitmode)
14. Wargoal tooltip in germany.122 now will target recipient (source: bitmode)
15. Fortify Shanghai focus no longer reduces fort level (source: myEmperor)

## U2 - 2025-05-09
1. In addition to changed AI attitudes, there's now a timed idea added in case of Munich Betrayal that will prevent ENG and FRA from giving guarantees for 30 days so they won't join the war against GER
2. The AI will now have higher priority for certain ideas in ai_strategy_plans (source: bitmode)
3. The AI is now able to change ideology using a political advisor if historical focuses are turned off (source: bitmode) with special conditions for some countries
4. It is no longer mandatory to complete the Australian national focus Empower the Workers to be able to pick democratic political advisor, also correctly attributed availability to AST_adopt_westminster

## U1 - 2025-05-03
1. It is no longer possible to build static AA if you don't have the first AA tech which is supposed to unlock it (source: Rikai)
2. AI FRA will be less likely to give up Indochina when at war with a weak enemy (source: Warden2054)

## Initial release - 2025-05-03
1. Japan is now required to control North Korea before it can fire Test the Soviets (source: ecpgieicg)
2. Only one Rebuild the Nation decision will now be available if you switch ideology using a civil war as in 1.6.1 patch
3. The game should now correctly check for autonomy levels in the SAF's fascist/communist NFs (source: bitmode)
4. china.111 (No longer united) now properly gives the PRC every CHI core northeast of Shanxi (source: bitmode)
5. Changed ENG attitude in an attempt to stop them giving back guarantees to CZE after Munich event
6. Azores lease return event will now only fire once as in 1.6 patch
7. The word antipodean is now spelled correctly in the focus "Rule them all" in the NZL focus tree (source: Orthano)
8. TRIGGER_DIVISIONS_LESS_THAN now properly says "Has less than $AMOUNT|H$ divisions" instead of "Has at least $AMOUNT|H$ divisions" (this incorrect wording still exists as of 1.16.8 patch lol)
9. Gannan has been moved into the same supply region as the rest of XSM as in 1.9 patch