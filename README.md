# Dota 2 Command list

| command  | default values | type command | description |
| ------------- | ------------- | ------------- | ------------- |
|_fov|0|cl|Automates fov command to server.|
|_record|cmd|norecord,release|Record a demo incrementally.|
|achievement_debug|false|sv,cl,rep,cheat|Turn on achievement debug msgs.|
|achievement_disable|false|sv,rep,cheat|Turn off achievements.|
|activategameui|cmd|cl||
|addip|cmd||Add an IP address to the ban list.|
|addons|cmd||list current addon info.|
|adsp_alley_min|122|||
|adsp_courtyard_min|126|||
|adsp_debug|0|a||
|adsp_door_height|112|||
|adsp_duct_min|106|||
|adsp_hall_min|110|||
|adsp_low_ceiling|108|||
|adsp_opencourtyard_min|126|||
|adsp_openspace_min|130|||
|adsp_openstreet_min|118|||
|adsp_openwall_min|130|||
|adsp_room_min|102|||
|adsp_street_min|118|||
|adsp_tunnel_min|114|||
|adsp_wall_height|128|||
|aghsfort_hero_undying_max_zombies|64|sv|AGHSFORT - Maximum amount of zombies that can be spawned.|
|ai_debug_dyninteractions|0|sv,cheat|Debug the NPC dynamic interaction system.|
|ai_debug_los|0|sv,cheat|NPC Line-Of-Sight debug mode. If 1, solid entities that block NPC LOC will be highlighted with white bounding boxes. If 2, it'll show non-solid entities that would do it if they were solid.|
|ai_debug_off_nav|false|sv,cheat||
|ai_debug_ragdoll_magnets|false|sv||
|ai_debug_shoot_positions|0|sv,cl,rep,cheat||
|ai_debug_soundent|0|sv|Reports sounds being entered into the AI sound list. Set to 1 to see all sounds, set to 2 to only see DANGER sounds.|
|ai_debug_soundent_duration|0.1|sv|Length of time to display ai_debug_soundent visual displays.|
|ai_debug_speech|0|sv||
|ai_disabled|false|sv,cl,rep,cheat||
|ai_expression_frametime|0.05|sv|Maximum frametime to still play background expressions.|
|ai_expression_optimization|false|sv|Disable npc background expressions when you can't see them.|
|ai_force_serverside_ragdoll|false|sv||
|ai_sequence_debug|false|sv,cl,rep||
|ai_show_current_nav|false|sv,cheat||
|ai_use_visibility_cache|1|sv|Sets whether or not NPCs can cache their Visibility checks against other entities. If set to 2, also tests to make sure that NPC->Target results match that of Target->NPC.|
|alias|cmd|release|Alias a command.|
|anim_disable|false|sv,cl,rep||
|anim_resource_validate_on_load|true|release|Validates the animation group channel list against the animations on load for every animation|
|anim_showmainactivity|false|cl,cheat|Show the idle, walk, run, and/or sprint activities.|
|animated_material_attributes|true|cl,cheat||
|animevents_dump|cmd|sv,cheat|List all the currently registered anim events. |
|animgraph_debug|false|sv,cl,rep,cheat|Debug animation graph|
|animgraph_debug_entindex|0|sv,cl,rep,cheat|The entity to specifically debug|
|animgraph_debug_filterent|0|sv,cl,rep|Filter setting for animgraph_debug_variables output. If set to -1, show debug for all entities. If set to 0, show debug for any NPCs that have been npc_selected. If set to >0, something other than 0, show debug for the entity with the matching entindex.|
|animgraph_debug_set_filter_params|0|sv,cl,rep|Comma separated list of params to filter against when drawing debug text overlays|
|animgraph_debug_tags|false|sv,cl,rep||
|animgraph_debug_variables|false|sv,cl,rep|Turn on to see animgraph variable changes for entities passing animgraph_debug_filterent.|
|animgraph_debug_variables_ignore_missing|true|sv,cl,rep|If set, animgraph_debug_variables won't show debug for warnings about sets to missing variables.|
|animgraph_debug_variables_ignore_nonchanges|true|sv,cl,rep|If set, animgraph_debug_variables won't show debug for variable sets that don't change the value.|
|animgraph_draw_traces|false|sv,cl,rep||
|animgraph_enable_dirty_netvar_optimization|true|||
|animgraph_enable_parallel_update|true|sv,cl,rep||
|animgraph_footlock_auto_ledge_detection|true|rep|Attempt to detect when the foot is partially hanging off a ledge and stop it tilting to reach the bottom|
|animgraph_footlock_auto_stair_detection|true|rep|Attempt to detect when the foot is on a stair and will stop it from tilting to reach the next step|
|animgraph_footlock_calculate_tilt|true|rep||
|animgraph_footlock_debug_foot_index|-1|rep||
|animgraph_footlock_debug_type|2|rep||
|animgraph_footlock_draw_footbase|false|||
|animgraph_footlock_enabled|true|rep|A master convar that effectively disables the entire footlock node.|
|animgraph_footlock_ground_roll|true|||
|animgraph_footlock_hip_offset_enable|true|||
|animgraph_footlock_ik_enable|true|cheat|Enable IK.|
|animgraph_footlock_tilt_mode|1|||
|animgraph_footlock_trace_ground_enabled|true|rep|Convar for toggling foot lock ground tracking.|
|animgraph_footlock_use_hip_shift|true|||
|animgraph_force_full_network_updates|false|||
|animgraph_force_tick_all_graphs|false|sv,cl,rep||
|animgraph_ik_debug|false|||
|animgraph_motionmatching_print_compressionstats|false|rep||
|animgraph_record_all|false|sv,cl,rep,cheat|Automatically start recording AnimGraphs when they get created, and save them to disk when they are destroyed|
|animgraph_slope_draw_raycasts|false|sv,cl,rep,cheat||
|animgraph_slope_enable|true|sv,cl,rep,cheat||
|animgraph_slowdownonslopes_enabled|true|rep||
|animgraph_trace_ignore_prop_physics|true|sv,cl,rep||
|animgraph_trace_static_only|false|sv,cl,rep,cheat||
|animgraph_verify_dirty_netvar_optimization|false|||
|assetbrowser|cmd|vconsole_set_focus|Show the global asset browser.|
|assetbrowser_name_filter_delay|250||Millisecond delay between typing in the assetbrowser filter and the filter being applied|
|assetsystem_check_compile_state|cmd||Perform a detailed check of an asset's compile state|
|assetsystem_clear_thumbnail_cache|cmd||Clear thumbnail cache|
|assetsystem_count|cmd||Find the number of assets registered with the asset system|
|assetsystem_debug_substring|0||Spew info for assets that match the specified substring|
|assetsystem_dump_string_threshold|2000||Max length of strings to dump in assetsystem_dump_table|
|assetsystem_dump_table|cmd|linked|Print internal assetsystem data.|
|assetsystem_legacy_explicit_reload_child_resources|false||Whether to explicitly reload child resources of a QueueReloadIfLoaded|
|assetsystem_legacy_process_file_changes_after_compile|false||Use old behavior of calling ProcessFileChanges() immediately after recompiling a resource|
|assetsystem_old_loop_algorithm|true||Set to true to revert to old behavior|
|assetsystem_quiet_inputs_before_recompile|true||Before triggering a resource recompile, wait for input dependencies to stop being written|
|assetsystem_quiet_inputs_before_recompile_max_pause|1000||Max amount of time to wait (in ms) for input dependencies to stop being written before abandoning the compile|
|assetsystem_quiet_inputs_before_reload|true||Before triggering a resource reload, wait for input dependencies to stop being written|
|assetsystem_reload_queue_requeue_pause|1||Time (sec) to pause assetsystem reload behavior if a requeue is requested|
|assetsystem_stats|cmd|linked|Information about the current assetsystem database.|
|assetsystem_test_resort|cmd|linked|(Dev command - regenerate the asset sort indicies)|
|assetthumbnail_old_fingerprint_style|true||Set to true to revert to old behavior|
|async_serialize|false||Force async reads to serialize for profiling|
|auto_bug|cmd|norecord|auto_bug |
|autosave|cmd|sv|Autosave|
|autosave_fully_async|true|sv|Set to 1 to have autosaves execute completely on the save thread, forces 'render only' mode while the save completes|
|autosavedangerous|cmd|sv|AutoSaveDangerous|
|autosavedangerousissafe|cmd|sv||
|axis|cmd|sv,cheat|Draw an axis  Arguments|
|banid|cmd||Add a user ID to the ban list.|
|banip|cmd||Add an IP address to the ban list.|
|battery_saver|false|a|OBSOLETE replaced by mobile_fps_* - Battery saver mode. 0=off, 1=on|
|benchframe|cmd|release|Takes a snapshot of a particular frame in a time demo.|
|bind|cmd|release|Bind a key.|
|binddefaults|cmd|release|Bind all keys to their default values.|
|bindss|cmd|release|Bind a key for a particular splitscreen player.|
|bindtoggle|cmd||Performs a bind <key> 'increment var <cvar> 0 1 1'.|
|blink|cmd|norecord|Blink specified convar value between two values at the specified duration.|
|blink_duration|0.5|cl|How many seconds an eye blink will last.|
|bot_mimic|0|cl,rep,cheat||
|bot_mimic_spec_buttons|true|cl,cheat|+attack, +jump etc are used for spectator control instead of being passed on to spectated bot|
|box|cmd|sv,cheat|Draw a bbox  Arguments|
|break_damage_inherit_scale|1|sv,cl,rep||
|break_invulnerable_spawn_duration|0.5|sv,cl,rep||
|breakable_multiplayer|true|sv||
|broadcaster_addfacts|cmd|cl||
|broadcaster_annotatefacts|cmd|cl||
|broadcaster_build_ability_movie_loc|cmd|cl||
|broadcaster_openmenu|cmd|cl||
|broadcaster_openquickstats|cmd|cl||
|broadcaster_quickstats_baselen|6|cl||
|broadcaster_quickstats_image_mode|false|cl||
|broadcaster_quickstats_len|9|cl||
|broadcaster_quickstats_maxl|200|cl||
|broadcaster_quickstats_minl|100|cl||
|broadcaster_quickstats_minmovielen|10|cl||
|broadcaster_quickstatsleague|0|cl||
|broadcaster_reloadfacts|cmd|cl||
|broadcaster_setsecondaryquickstats|cmd|cl||
|broadcaster_togglegreenscreen|cmd|cl||
|buddha|false|sv,nf,cheat|Player takes damage but won't die|
|buddha_ignore_bots|false|sv,nf,cheat|Bots always buddha 0|
|buddha_reset_hp|1|sv,nf,cheat|HP to set when damaged below zero in Buddha Mode|
|bug|cmd|norecord|bug [auto_fill_tokens] [-title <text>] [-noscreenshot] |
|bug_submitter_override|0|a||
|+bugvoice|cmd|norecord|Start recording bug voice attachment.|
|bugvoice_clear|cmd|norecord|Clear voice attachment data.|
|bugvoice_save|cmd|norecord|Write buffered voice attachment data to file.|
|buildcubemaps|cmd|cl|Build Cubemaps|
|c_maxdistance|200|cl,a||
|c_maxpitch|90|cl,a||
|c_maxyaw|135|cl,a||
|c_mindistance|30|cl,a||
|c_minpitch|0|cl,a||
|c_minyaw|-135|cl,a||
|c_orthoheight|100|cl,a||
|c_orthowidth|100|cl,a||
|c_thirdpersonshoulder|false|cl,a||
|c_thirdpersonshoulderaimdist|120|cl,a||
|c_thirdpersonshoulderdist|40|cl,a||
|c_thirdpersonshoulderheight|5|cl,a||
|c_thirdpersonshoulderoffset|20|cl,a||
|cam_collision|1|cl,a|When in thirdperson and cam_collision is set to 1, an attempt is made to keep the camera from passing though walls.|
|cam_command|cmd|cl,cheat|Tells camera to change modes|
|cam_idealdelta|4|cl,a|Controls the speed when matching offset to ideal angles in thirdperson view|
|cam_idealdist|150|cl,a||
|cam_ideallag|4|cl,a|Amount of lag used when matching offset to ideal angles in thirdperson view|
|cam_idealpitch|0|cl,a||
|cam_idealyaw|0|cl,a||
|cam_showangles|false|cl,cheat|When in thirdperson, print viewangles/idealangles/cameraoffsets to the console.|
|cam_snapto|false|cl,a||
|+camdistance|cmd|cl||
|camerazoomin|cmd|cl||
|camerazoomout|cmd|cl||
|+cammousemove|cmd|cl||
|camortho|cmd|cl,cheat|Switch to orthographic camera.|
|cancelselect|cmd|cl,server_can_execute||
|capturecubemap|cmd|cl|Capture Cubemap|
|cast_aabb|cmd|sv,cheat|Tests box collision detection|
|cast_capsule|cmd|sv,cheat|Tests capsule collision detection|
|cast_convex|cmd|sv,cheat|Tests convex hull collision detection|
|cast_cylinder|cmd|sv,cheat|Tests cylinder collision detection|
|cast_intervals|cmd|sv,cheat|Tests interval ray cast|
|cast_obb|cmd|sv,cheat|Tests cylinder collision detection|
|cast_physics|cmd|sv,cheat|Tests physics shape collision detection|
|cast_ray|cmd|sv,cheat|Tests ray cast|
|cast_sphere|cmd|sv,cheat|Tests sphere cast|
|cavern_crawl_pregame_intro_shown|0|cl,a||
|cc_captiontrace|1|cl|Show missing closecaptions (0 = no, 1 = devconsole, 2 = show in hud)|
|cc_delay_time|0.25|cl,a|Close caption delay before showing caption.|
|cc_emit|cmd|cl|Emits a closed caption|
|cc_findsound|cmd|cl|Searches for soundname which emits specified text.|
|cc_flush|cmd|cl|Flushes async'd captions.|
|cc_lang|0|cl,a|Current close caption language (emtpy = use game UI language)|
|cc_linger_time|1|cl,a|Close caption linger time.|
|cc_log|0|cl|Log caption names and contents (0 = off, 1 = found captions, 2 = unfound captions, 3 = all captions)|
|cc_norepeat|5|sv|In multiplayer games, don't repeat captions more often than this many seconds.|
|cc_random|cmd|cl|Emits a random caption|
|cc_showblocks|cmd|cl|Toggles showing which blocks are pending/loaded async.|
|cc_showmissing|false|sv,rep|Show missing closecaption entries.|
|cc_spectator_only|false|cl,a||
|cc_subtitles|false|cl,a|If set, don't show sound effect captions, just voice overs (i.e., won't help hearing impaired players).|
|cc_vr_caption_catchup_interval|0.3|cl|Duration it takes for attached caption to ideal point|
|cc_vr_caption_speed|1|cl,a|0 = slow, 1 = medium (default), 2 = fast|
|cc_vr_debug|false|cl|Debug visualization of VR closed caption placement|
|cc_vr_depth_test|false|cl|Have closed caption Panorama panel perform depth testing against the scene|
|cc_vr_epsilon|2.5|cl|Epsilon to trigger movement of VR subtitle panel in world space|
|cc_vr_font_size|1|cl,a|0 = small, 1 = med (default), 2 = large|
|cc_vr_forward_offset|30|cl|Subtitle offset distance (forward, in front of player)|
|cc_vr_vertical_offset|-6.5|cl|Subtitle vertical offset distance (positive is up)|
|cc_vr_width|1|cl,a|0 = narrow, 1 = med (default), 2 = wide|
|changelevel|cmd|release|changelevel <mapname> |
|chat_channel_debug|cmd|cl|Print members of a chat channel|
|chat_join|cmd|cl|Join a chat channel|
|chat_join_hltv|cmd|cl|Join an hltv chat channel|
|chat_leave|cmd|cl|Leave a chat channel|
|chat_say|cmd|cl|Send a message to the specified channel|
|chat_sound|true|cl,a,per_user|If enabled, play sound when receiving chat messages|
|chat_wheel_emoticon_0|0|cl,a,per_user||
|chat_wheel_emoticon_1|0|cl,a,per_user||
|chat_wheel_emoticon_10|0|cl,a,per_user||
|chat_wheel_emoticon_11|0|cl,a,per_user||
|chat_wheel_emoticon_12|0|cl,a,per_user||
|chat_wheel_emoticon_13|0|cl,a,per_user||
|chat_wheel_emoticon_14|0|cl,a,per_user||
|chat_wheel_emoticon_15|0|cl,a,per_user||
|chat_wheel_emoticon_2|0|cl,a,per_user||
|chat_wheel_emoticon_3|0|cl,a,per_user||
|chat_wheel_emoticon_4|0|cl,a,per_user||
|chat_wheel_emoticon_5|0|cl,a,per_user||
|chat_wheel_emoticon_6|0|cl,a,per_user||
|chat_wheel_emoticon_7|0|cl,a,per_user||
|chat_wheel_emoticon_8|0|cl,a,per_user||
|chat_wheel_emoticon_9|0|cl,a,per_user||
|chat_wheel_phrase_0|624|cl,a,per_user||
|chat_wheel_phrase_1|625|cl,a,per_user||
|chat_wheel_phrase_10|79|cl,a,per_user||
|chat_wheel_phrase_11|66|cl,a,per_user||
|chat_wheel_phrase_12|80|cl,a,per_user||
|chat_wheel_phrase_13|61|cl,a,per_user||
|chat_wheel_phrase_14|62|cl,a,per_user||
|chat_wheel_phrase_15|70|cl,a,per_user||
|chat_wheel_phrase_2|628|cl,a,per_user||
|chat_wheel_phrase_3|626|cl,a,per_user||
|chat_wheel_phrase_4|595|cl,a,per_user||
|chat_wheel_phrase_5|76|cl,a,per_user||
|chat_wheel_phrase_6|75|cl,a,per_user||
|chat_wheel_phrase_7|651|cl,a,per_user||
|chat_wheel_phrase_8|65|cl,a,per_user||
|chat_wheel_phrase_9|69|cl,a,per_user||
|+chatwheel|cmd|cl|Opens chatwheel menu while held|
|+chatwheel2|cmd|cl|Opens the second chatwheel menu while held|
|chatwheel_say|cmd|cl|Send a chatwheel message. Usage|
|cl_aggregate_particles|false|||
|cl_anglespeedkey|0.67|cl||
|cl_anim_queue_changes|true|cl||
|cl_animgraph_history_force_temporal_consistency|true|cl||
|cl_auto_cursor_scale|false|a|Automatic cursor size scaling.|
|cl_axis|cmd|cl,cheat|Draw an axis  Arguments|
|cl_box|cmd|cl,cheat|Draw a bbox  Arguments|
|cl_cache_sendtable|true||Cache sendtables|
|cl_cameraoverride_fade_in_amount|0|cl||
|cl_cameraoverride_shadow_depth_bias|0.006|cl||
|cl_cameraoverride_shadow_end|0.8|cl||
|cl_change_callback_limit|0.2|cl,release|change callback msec warning limit|
|cl_chat_active|0|cl||
|cl_checkdeclareclasses|cmd|cheat|Check game code serializers|
|cl_clock_correction|true|cheat|Enable/disable clock correction on the client.|
|cl_clock_correction_adjustment_max_amount|200|cheat|Sets the maximum number of milliseconds per second it is allowed to correct the client clock. It will only correct this amount if the difference between the client and server clock is equal to or larger than cl_clock_correction_adjustment_max_offset.|
|cl_clock_correction_adjustment_max_offset|90|cheat|As the clock offset goes from cl_clock_correction_adjustment_min_offset to this value (in milliseconds), it moves towards applying cl_clock_correction_adjustment_max_amount of adjustment. That way, the response is small when the offset is small.|
|cl_clock_correction_adjustment_min_offset|10|cheat|If the clock offset is less than this amount (in milliseconds), then no clock correction is applied.|
|cl_clock_correction_force_server_tick|999|cheat|Force clock correction to match the server tick + this offset (-999 disables it).|
|cl_clock_showdebuginfo|0||Show debugging info about the clock drift, 1= resets, 2=adjustments, 3=verbose|
|cl_clock_unhook|false|||
|cl_clockdbg|false|||
|cl_clockdrift_max_ticks|3|cheat|Maximum number of ticks the clock is allowed to drift before the client snaps its clock to the server's.|
|cl_commandtool_exec|cmd|cl|Runs a command from the command tool|
|cl_connectionretrytime_p2p|20|release|Number of seconds over which to spread retry attempts for P2P.|
|cl_cq_min_queue|0|cl,user|Allows client to disable (=-1), defer to server (=0), or request a certain min-command queue size for games that support the command queue (IsUsingCommandQueue()) for CUserCmds.|
|cl_cursor_scale|0.846916|a|Cursor size scaling factor.|
|cl_debug_overlay_fullposition|false|cl||
|cl_debug_overlays_broadcast|false|release|Render debug overlays from server.|
|cl_debugoverlay_cycle_domain|cmd|cl,cheat|Toggles visibility of the debug overlay system.|
|cl_debugoverlay_cycle_state|cmd|cl,cheat|Toggles visibility of the debug overlay system.|
|cl_debugoverlay_hide_imgui|cmd|cl,cheat|Hides the overlay.|
|cl_debugoverlay_toggle|cmd|cl,cheat|Toggles visibility of the debug overlay system.|
|cl_decal_clear_all_entities|cmd|cl|Clears decals from all entities|
|cl_decal_clear_world|cmd|cl|Clears world decals|
|cl_decal_debug|cmd|cl|Toggles client decal debug visualization|
|cl_decal_shoot|cmd|cl|Shoots a client-side decal|
|cl_demo_steadycam_blendframes|5|cl|blend over this many frames|
|cl_demo_steadycam_deflection|5|cl|if camera orientation changes this much update orientation|
|cl_demo_steadycam_enable|0|cl|Stabilize camera orientation/position during demo playback.  1 == remove roll, 2 == steadycam|
|cl_demo_steadycam_radius|16|cl|if camera moves this much from last anchor update anchor|
|cl_demo_view_offset_left|0|cl|View offset during demo playback (+/- 1.25 is a good default for human average left/right eye offset)|
|cl_demoviewoverride|0|cl|Override view during demo playback|
|cl_destroy_ragdolls|cmd|cl|Destroys all client-side ragdolls|
|cl_disable_ragdolls|false|cl,cheat||
|cl_disconnect_soundevent|core.stop_all_soundevents||This soundevent is called to stop the desired soundevents when the game is disconnected.|
|cl_disconnect_voice_fade|2||This is a fade of current voices that is called when the game is disconnected. -1.f for no fade on disconnect|
|cl_display_game_events|false|cl,cheat||
|cl_dormant_spew|false|cl|Spew state on when client entities become dormant or active.|
|cl_dota_alt_unit_movetodirection|false|cl,a|Does holding alt enable move to direction mode?|
|cl_dota_ambient_tree_shake|false|cl||
|cl_dota_ambient_tree_shake_cooldown|2|cl||
|cl_dota_ambient_tree_shake_duration|0.5|cl||
|cl_dota_ambient_tree_shake_peak_time|0.1|cl||
|cl_dota_ambient_tree_shake_range|128|cl||
|cl_dota_ambient_tree_shake_strength|2|cl||
|cl_dota_cache_hitboxes_model_bind_pose|false|cl||
|cl_dota_cd_captain_pick_time|10|cl,cheat||
|cl_dota_dump_econ_item_stringtable|cmd|cl|cl_dota_dump_econ_item_stringtable|
|cl_dota_dump_modifier_stringtable|cmd|cl|cl_dota_dump_modifier_stringtable|
|cl_dota_gridnav_show|0|cl,cheat||
|cl_dota_gridnav_show_size|1|cl,cheat|Control the size of the gridnav display. 1 = small, 2 = medium, 3 = large|
|cl_dota_mk_tree_shake_duration|2|cl||
|cl_dota_mk_tree_shake_peak_time|0.25|cl||
|cl_dota_mk_tree_shake_strength|15|cl||
|cl_dota_recent_games_include_custom_games|false|cl,a||
|cl_dota_recent_games_include_event_games|false|cl,a||
|cl_dota_recent_games_include_practice_matches|false|cl,a||
|cl_dota_showents|cmd|cl,cheat|Dump entity list to console.|
|cl_dota_speech_spec_ancientattack|true|cl|Set to 0 to prevent hearing 'your ancient is under attack' lines.|
|cl_dota_speech_spec_barracksattack|true|cl|Set to 0 to prevent hearing 'your rax is under attack' lines.|
|cl_dota_speech_spec_barracksfalls|true|cl|Set to 0 to prevent hearing 'your rax has fallen' lines.|
|cl_dota_speech_spec_enemybasefalls|true|cl|Set to 0 to prevent hearing 'enemy's tower/rax has fallen' lines.|
|cl_dota_speech_spec_idles|true|cl|Set to 0 to prevent hearing announcers' idle lines.|
|cl_dota_speech_spec_towerattack|true|cl|Set to 0 to prevent hearing 'your tower is under attack' lines.|
|cl_dota_speech_spec_towerfalls|true|cl|Set to 0 to prevent hearing 'your tower has fallen' lines.|
|cl_dota_unified_tree_hitboxes|true|cl||
|cl_draw_simulating_entities|false|cl||
|cl_draw_simulating_entities_distance|false|cl||
|cl_drawcross|cmd|cl,cheat|Draws a cross at the given location  Arguments|
|cl_drawhud|true|cl,cheat|Enable the rendering of the hud|
|cl_drawline|cmd|cl,cheat|Draws line between two 3D Points.  Green if no collision  Red is collides with something  Arguments|
|cl_dump_anim_list|cmd|cl||
|cl_dump_modifier_list|cmd|cl|Dumps all modifiers that exist in the game|
|cl_dump_projected_texture_count|cmd|cl|Print out number of active projected textures|
|cl_dumpentity|cmd|cl,cheat|Dumps info about an entity|
|cl_dumpsplithacks|cmd|cl|Dump split screen workarounds.|
|cl_enable_eye_occlusion|true|cl||
|cl_ent_absbox|cmd|cl,cheat|Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.  Arguments|
|cl_ent_actornames|cmd|cl,cheat|Displays the entity name for all entities that have ShouldDisplayInActorNames true in code|
|cl_ent_animgraph_debug|cmd|cl,cheat|Displays debug draws about the given entity(ies) animgraph  Arguments|
|cl_ent_animgraph_record|cmd|cl,cheat|Toggles recording of animgraph replay of the given entity(s)  Arguments|
|cl_ent_attachments|cmd|cl,cheat|Displays the attachment points on an entity.  Arguments|
|cl_ent_bbox|cmd|cl,cheat|Displays the movement bounding box for the given entity(ies) in orange.  Some entites will also display entity specific overlays.  Arguments|
|cl_ent_call|cmd|cl,cheat|ent_call <funcname> <option|
|cl_ent_clear_debug_overlays|cmd|cl,cheat|Clears all debug overlays|
|cl_ent_find|cmd|cl,cheat|Find and list all entities with classnames or targetnames that contain the specified substrings. Format|
|cl_ent_find_index|cmd|cl,cheat|Display data for entity matching specified index. Format|
|cl_ent_grab|cmd|cl,cheat|grabs the object in front of the player. Options|
|cl_ent_hierarchy|cmd|cl,cheat|Prints the entity hierarchy tree rooted at the specified ent(s)|
|cl_ent_hitbox|cmd|cl,cheat|Displays the hitboxes for the given entity(ies).  Arguments|
|cl_ent_joint_axis_size|4|cl||
|cl_ent_joint_filter_substring|0|cl||
|cl_ent_joint_names|true|cl||
|cl_ent_joint_only_ik_joints|false|cl||
|cl_ent_joint_use_bind_pose|false|cl||
|cl_ent_joints|cmd|cl,cheat|Displays the joint names + axes an entity.  Arguments|
|cl_ent_messages|cmd|cl,cheat|Toggles input/output message display for the selected entity(ies).  The name of the entity will be displayed as well as any messages that it sends or receives.  Arguments|
|cl_ent_name|cmd|cl,cheat|Displays the entity name|
|cl_ent_picker|cmd|cl,cheat|Toggles 'picker' mode.  When picker is on, the bounding box, pivot and debugging text is displayed for whatever entity the player is looking at.  Arguments|
|cl_ent_pivot|cmd|cl,cheat|Displays the pivot for the given entity(ies).  (y=up=green, z=forward=blue, x=left=red).   Arguments|
|cl_ent_pivot_size|20|cl,a,cheat||
|cl_ent_remove|cmd|cl,cheat|Removes the given entity(s)  Arguments|
|cl_ent_remove_all|cmd|cl,cheat|Removes all entities of the specified type  Arguments|
|cl_ent_scale|cmd|cl,cheat|Scales entities. Arguments|
|cl_ent_scenehierarchy|cmd|cl,cheat|Prints the entity scenenode hierarchy tree rooted at the specified ent(s)|
|cl_ent_script_dump|cmd|cl,cheat|Dumps the names and values of this entity's script scope to the console  Arguments|
|cl_ent_select|cmd|cl,cheat|Select or deselects the given entities(s) for later manipulation  Arguments|
|cl_ent_setang|cmd|cl,cheat|Set entity angles|
|cl_ent_setname|cmd|cl,cheat|Sets the targetname of the given entity(s)  Arguments|
|cl_ent_setpos|cmd|cl,cheat|Move entity to position|
|cl_ent_show_contexts|false|cl,cheat|Show entity contexts in ent_text display|
|cl_ent_show_damage|cmd|cl,cheat|Sets damage display mode.  When on, you will see the amount of damage dealt over the target's head.|
|cl_ent_showonlyattachment|0|cl,cheat||
|cl_ent_showonlyhitbox|-1|cl,cheat||
|cl_ent_skeleton|cmd|cl,cheat|Displays the skeleton for the given entity(ies).  Arguments|
|cl_ent_skeleton_only_ik_joints|false|cl||
|cl_ent_text|cmd|cl,cheat,vconsole_fuzzy|Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text256|cmd|cl,cheat|Displays text debugging information about the given entity(ies) [within 256 units of the player] on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text_clear|cmd|cl,cheat|Hide text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text_filter|cmd|cl,cheat|Set which ent_text filters you want|
|cl_ent_text_flags_active|-1|cl,a,cheat||
|cl_ent_text_no_name_really_i_mean_it|false|cl,cheat||
|cl_ent_text_radius|cmd|cl,cheat|Displays text debugging information about the given entity(ies) [near the player] on top of the entity (See Overlay Text)  2 Arguments|
|cl_ent_text_sticky_add|cmd|cl,cheat|Adds to list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text_sticky_clear|cmd|cl,cheat|Clears the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text_sticky_dump|cmd|cl,cheat|Spews the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_text_sticky_remove|cmd|cl,cheat|Removes from the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|cl_ent_ungrab|cmd|cl,cheat|un-grabs all objects|
|cl_ent_vcollide_wireframe|cmd|cl,cheat|Displays the interpolated vcollide wireframe pm am entity.  Arguments|
|cl_ent_viewoffset|cmd|cl,cheat|Displays the eye position for the given entity(ies) in red.  Arguments|
|cl_entityreport|cmd|cl|Reports all extant entities. Optional 2nd arg is a substring of a classname that the list will be filtered by.|
|cl_entitysummary|cmd|cl|Summarizes (by class) all extant entities. Optional 2nd arg is a substring of a classname that the list will be filtered by.|
|cl_ents|cmd|cl|List client entities, sorted by spawn group|
|cl_error_report_time|0|cl,release|Minimum time in seconds that must elapse before printing prediction error summary. 0 to disable.|
|cl_extrapolate|false|cl,cheat|Enable/disable extrapolation if interpolation history runs out.|
|cl_extrapolate_amount|0.25|cl,cheat|Set how many seconds the client will extrapolate entities for.|
|cl_eye_occlusion_debug|false|cl,cheat||
|cl_eye_sin_wave|false|cl||
|cl_eye_target_override|0.0000000.0000000.000000|cl||
|cl_eye_yaw_multiplier|1|cl||
|cl_fasttempentcollision|5|cl||
|cl_flushentitypacket|0|cheat|For debugging. Force the engine to flush an entity packet.|
|cl_fullupdate|cmd|cheat|Force uncompressed update|
|cl_globallight_debug|false|cl||
|cl_globallight_depth_bias|-999|cl||
|cl_globallight_expansion|200|cl||
|cl_globallight_freeze|false|cl||
|cl_globallight_orig_calc_frustum|true|cl||
|cl_globallight_shadow_mode|0|cl||
|cl_globallight_slope_scale_depth_bias|-999|cl||
|cl_globallight_use_alt_focus_region|false|cl||
|cl_globallight_use_optimized_calc_frustum|true|cl||
|cl_globallight_use_shaadow_near_offset|true|cl||
|cl_globallight_world_bottom_height|0|cl||
|cl_globallight_world_top_height|4096|cl||
|cl_glow_brightness|1|cl,cheat|Brightness of player halos|
|cl_glow_item_far_b|1|cl,release||
|cl_glow_item_far_g|0.4|cl,release||
|cl_glow_item_far_r|0.3|cl,release||
|cl_groups|cmd|cl|Show status of all spawn groups.|
|cl_hitbox_debug|false|cl||
|cl_hold_game_events_force_delay_ticks|0|cl|Debugging convar to force late dispatch of game events.|
|cl_hold_game_events_until_server_tick|true|cl|Holds game events until client has received the tick the event was fired on.|
|cl_ignorepackets|false|cheat|Force client to ignore packets (for debugging).|
|cl_imgui_set_selection|cmd|cl,cheat|Sets ImGui selection|
|cl_imgui_set_status_text|cmd|cl,cheat|Sets ImGui header status text|
|cl_interp|0.033|cl,user|Sets the interpolation amount (bounded on low side by server interp ratio settings).|
|cl_interp_all|false|cl|Disable interpolation list optimizations.|
|cl_interp_animationvars|true|cl|Interpolate LATCH_ANIMATION_BIT vars if interpolation interval is greater than simulation interval|
|cl_interp_hermite|true|cl,cheat|Set to zero do disable hermite interpolation.|
|cl_interp_npcs|0|cl|Interpolate NPC positions starting this many seconds in past (or cl_interp, if greater)|
|cl_interp_ratio|1|cl,user|Sets the interpolation amount (final amount is cl_interp_ratio / cl_updaterate).|
|cl_interp_simulationvars|true|cl|Interpolate LATCH_SIMULATION_BIT vars if interpolation interval is greater than animation interval|
|cl_interp_threadmodeticks|0|cl|Additional interpolation ticks to use when interpolating with threaded engine mode set.|
|cl_interpolate_report|false|cl,a|Enable to show interpolation profile timing |
|cl_jiggle_bone_debug|false|cheat|Display physics-based 'jiggle bone' debugging information|
|cl_jiggle_bone_debug_pitch_constraints|false|cheat|Display physics-based 'jiggle bone' debugging information|
|cl_jiggle_bone_debug_yaw_constraints|false|cheat|Display physics-based 'jiggle bone' debugging information|
|cl_jiggle_bone_invert|false|cheat||
|cl_jiggle_bone_sanity|true||Prevent jiggle bones from pointing directly away from their target in case of numerical instability.|
|cl_lagcompensation|true|cl,user|Perform server side lag compensation of weapon firing events.|
|cl_language|russian||Language|
|cl_latch_report|false|cl,a|Enable to output stats about latching|
|cl_leveloverview|0|cl,cheat||
|cl_lightquery_debug|false|cl,cheat||
|cl_lock_camera|false|cl,cheat||
|cl_log_tick|false||Log when a tick is received |
|cl_log_tick_skips|0||Log when the tick delta >= this|
|cl_massreport|false|cl||
|cl_mouselook|true|cl,a,user,per_user,disconnected|Set to 1 to use mouse for look, 0 for keyboard look. Cannot be set while connected to a server.|
|cl_net_showeventlisteners|false|cl|Show listening addition/removals|
|cl_net_showevents|0|cl|Dump game events to console (1=client only, 2=all).|
|cl_network_quality2|1|cl,a||
|cl_panel_freeze_time_after_press|0.5|cl|time to freeze mouse/pointer motion after a mouse button press|
|cl_panorama_script_help|cmd|cl,release|Display Panorama JavaScript bindings|
|cl_panorama_script_help_2|cmd|cl,release|Display all registered Panorama JavaScript bindings in wiki syntax|
|cl_panorama_typescript_declarations|cmd|cl,release|Display Panorama JavaScript bindings as TypeScript declarations|
|cl_parallel_readpacketentities|true||Set to 1 to use threading snapshot reading (if game supports and server is sending bitcounts).|
|cl_parallel_readpacketentities_threshold|8||Use parallel processing of snapshot reading if above this many entries.|
|cl_parallel_readpacketentities_type|-1||  -1 = use default (parallel controller split)  0 = single threaded combined (i.e., ReadFieldList and Decode combined into one call)  1 = single threaded split (first pass ReadFieldList, second pass Decode)  2 = worker thread for decode (main thread does ReadFieldList, worker thread does Decode)  3 = parallel combined (threadpool does read/decode on work items in parallel)  4 = parallel split  5 = parallel controller combined (like parallel, but uses a parallelcontroller so each thread in pool can share a single SerializedEntity  6 = parallel controller split |
|cl_particle_batch_mode|1|||
|cl_particle_fallback_base|0||Base for falling back to cheaper effects under load.|
|cl_particle_fallback_multiplier|0||Multiplier for falling back to cheaper effects under load.|
|cl_particle_log_creates|false||Print debug message every time a particle collection is created|
|cl_particle_max_count|0|||
|cl_particle_retire_cost|0|cheat||
|cl_particle_sim_fallback_base_multiplier|5||How aggressive the switch to fallbacks will be depending on how far over the cl_particle_sim_fallback_threshold_ms the sim time is.  Higher numbers are more aggressive.|
|cl_particle_sim_fallback_threshold_ms|6||Amount of simulation time that can elapse before new systems start falling back to cheaper versions|
|cl_particle_simulate|true|cheat|Enables/Disables Particle Simulation|
|cl_particles_dump_effects|cmd|cl||
|cl_particles_dumplist|cmd|cl,linked|Dump all new particles, optional name substring.|
|cl_particles_dumpsimlist|cmd|cl,linked|Dump all simulating particles, optional name substring.|
|cl_pclass|0|cl,cheat|Dump entity by prediction classname.|
|cl_pdump|-1|cl,cheat|Dump info about this entity to screen.|
|cl_phys_animated_hierarchy|true|cl||
|cl_phys_block_dist|1|cl||
|cl_phys_block_fraction|0.1|cl||
|cl_phys_debug_callback_entities|false|cl,cheat|Print all entities that get touch callbacks. Each entity is printed only once.|
|cl_phys_enabled|true|cl,cheat|Enable all physics simulation|
|cl_phys_networked_start_sleep|false|cl||
|cl_phys_sleep_enable|true|cl,cheat|Enable sleeping for dynamic physics bodies.|
|cl_phys_stop_at_collision|0|cl,cheat||
|cl_phys_timescale|1|cl|Scale time for physics|
|cl_phys_visualize_awake|false|cl||
|cl_pitchdown|89|cl,cheat||
|cl_pitchspeed|225|cl||
|cl_pitchup|89|cl,cheat||
|cl_playback_screenshots|false||Allows the client to playback screenshot and jpeg commands in demos.|
|cl_playerspraydisable|false|cl,a|Disable player sprays.|
|cl_portrait_bg_translucent_test|false|cl,cheat|Renders the hero on a gray background for translucency blending testing|
|cl_portrait_deferred|false|cl|Use deferred rendering for portraits.|
|cl_precacheinfo|cmd||Show precache info (client).|
|cl_pred_build_verbose|false|cl|Verbose spew when building prediction optimized data runs.|
|cl_pred_optimize|2|cl|Optimize for not copying data if didn't receive a network update (1), and also for not repredicting if there were no errors (2).|
|cl_pred_parallel_postnetwork|false|cl||
|cl_pred_track|cmd|cl|<entindex> <fieldname>|
|cl_pred_track_off|cmd|cl|clear field track changes.|
|cl_predict|false|cl,user,cheat|Perform client side prediction.|
|cl_predictioncopy_describe|cmd|cl|Describe datamap_t for entindex|
|cl_predictioncopy_print|cmd|cl|Print simple description of prediction copy fields for entindex|
|cl_predictioncopy_runs|true|cl||
|cl_predictweapons|true|cl,user|Perform client side prediction of weapon effects.|
|cl_printfps|cmd|cl|Print information from cl_showfps.|
|cl_prop_debug|cmd|cl,cheat|Toggle prop debug mode. If on, props will show colorcoded bounding boxes. Red means ignore all damage. White means respond physically to damage but never break. Green maps health in the range of 100 down to 1.|
|cl_querycache_stats|cmd|cl,cheat|Display status of the query cache (client only)|
|cl_ragdoll_limit|20|cl,a|Maximum number of ragdolls to show (-1 disables limit)|
|cl_ragdoll_lru_debug|false|cl,rep,cheat||
|cl_ragdoll_reload|false|cl||
|cl_removedecals|cmd|cl,cheat|Remove the decals from the entity under the crosshair.|
|cl_report_predcopy_overrides|cmd|cl|Report prediction copy overrides|
|cl_report_soundpatch|cmd|cl|reports client-side sound patch count|
|cl_resend|0.5|release|Delay in seconds before the client will resend the 'connect' attempt|
|cl_resetfps|cmd|cl|Reset information from cl_showfps.|
|cl_retire_low_priority_lights|false|cl|Low priority dlights are replaced by high priority ones|
|cl_rr_findrules|cmd|cl|Search and list rules by substring.|
|cl_rr_findrules_verbose|cmd|cl|Search and list rules by substring.|
|cl_rr_reloadresponsesystems|cmd|cl,cheat|Reload all response system scripts.|
|cl_save_animgraph_recording|cmd|cl,cheat|Saves all active animgraph recordings to disk|
|cl_sceneentity_debug|false|cl|Display all thinking scene entities and its data.|
|cl_screenmessage_notifytime|8|cl|How long to display screen message text|
|cl_script_add_debug_filter|cmd|cl,cheat|Add a filter to the game debug overlay|
|cl_script_add_watch|cmd|cl,cheat|Add a watch to the game debug overlay|
|cl_script_add_watch_pattern|cmd|cl,cheat|Add a watch to the game debug overlay|
|cl_script_attach_debugger|cmd|cl,cheat|Connect the vscript VM to the script debugger|
|cl_script_attach_debugger_at_startup|false|cl||
|cl_script_break_in_native_debugger_on_error|false|cl||
|cl_script_clear_watches|cmd|cl,cheat|Clear all watches from the game debug overlay|
|cl_script_debug|cmd|cl,cheat|Toggle the in-game script debug features|
|cl_script_dump_all|cmd|cl,cheat|Dump the state of the VM to the console|
|cl_script_find|cmd|cl,cheat|Find a key in the VM |
|cl_script_help|cmd|cl,cheat|Output help for script functions|
|cl_script_help2|cmd|cl|Output help for script functions suitable for auto-completion|
|cl_script_reload|cmd|cl,cheat|Reload scripts|
|cl_script_reload_code|cmd|cl,cheat|Execute a vscript file, replacing existing functions with the functions in the run script|
|cl_script_reload_entity_code|cmd|cl,cheat|Execute all of this entity's VScripts, replacing existing functions with the functions in the run scripts|
|cl_script_remove_debug_filter|cmd|cl,cheat|Remove a filter from the game debug overlay|
|cl_script_remove_watch|cmd|cl,cheat|Remove a watch from the game debug overlay|
|cl_script_remove_watch_pattern|cmd|cl,cheat|Remove a watch from the game debug overlay|
|cl_script_resurrect_unreachable|cmd|cl,cheat|Use the garbage collector to track down reference cycles|
|cl_script_trace_disable|cmd|cl,cheat|Turn off a particular trace output by file or function name|
|cl_script_trace_disable_all|cmd|cl,cheat|Turn off all trace output|
|cl_script_trace_disable_key|cmd|cl,cheat|Turn off a particular trace output by table/instance|
|cl_script_trace_enable|cmd|cl,cheat|Turn on a particular trace output by file or function name|
|cl_script_trace_enable_all|cmd|cl,cheat|Turn on all trace output|
|cl_script_trace_enable_key|cmd|cl,cheat|Turn on a particular trace output by table/instance|
|cl_sendtable_cache_filename|sendtables.bin||Send tables cache file|
|cl_sequence_debug|-1|cl||
|cl_sequence_debug2|-1|cl||
|cl_sequence_debug_verbose|true|cl||
|cl_sequence_model_substring|0|cl||
|cl_show_mouseclick_effects|true|cl||
|cl_showanimstate|-1|cl,cheat|Show the (client) animation state for the specified entity (-1 for none).|
|cl_ShowBoneSetupEnts|false|cl|Show which entities are having their bones setup each frame.|
|cl_showdemooverlay|0||How often to flash demo recording/playback overlay (0 - disable overlay, -1 - show always)|
|cl_showents|cmd|cl,cheat|Dump entity list to console.|
|cl_showerror|0|cl,release|Show prediction errors, 2 for above plus detailed field deltas, 3 to filter out serverside known prediction errors, -entindex for specific entity.|
|cl_showfps|0|cl,release|Draw fps meter at top of screen (1 = fps, 2 = smooth fps, 3 = server MS, 4 = Show FPS and Log to file )|
|cl_showmem|0|cl,release|Draw approximate memory use at top of screen|
|cl_showpos|0|cl,cheat,release|Draw current position at top of screen|
|cl_showtextmsg|true|cl|Enable/disable text messages printing on the screen.|
|cl_showusercmd|false|cl|Show user command encoding|
|cl_simulate_dormant_entities|true|cl||
|cl_skel_constraints_enable|true|rep,cheat||
|cl_skeleton_instance_smear_boneflags|false|cl,cheat|Smear boneflags across the model.  Costs computation, but tests to make sure your bone flags are consistent.|
|cl_smooth|true|cl|Smooth view/eye origin after prediction errors|
|cl_smoothtime|0.2|cl|Smooth client's view after prediction error over this many seconds|
|cl_snd_cast_clear|true|||
|cl_snd_cast_retrigger|true|||
|cl_snd_new_visualize|false|cl,cheat|Displays soundevent name played at it's 3d position|
|cl_soundscape_flush|cmd|cl,cheat,server_can_execute|Flushes the client side soundscapes|
|cl_soundscape_printdebuginfo|cmd|cl|print soundscapes|
|cl_spectator_interp_ratio|2|cl|When connected to hltv or playing a demo, adjust the interp time by this ratio.|
|cl_spewserializers|cmd|cheat|Spew serializers|
|cl_ss_origin|cmd|cl|print origin in script format|
|cl_test_list_entities|cmd|cl,cheat|test-list entities|
|cl_timeout|30|a|After this many seconds without receiving a packet from the server, the client will disconnect itself|
|cl_tracer_whiz_distance|72|cl||
|cl_tracer_whiz_infront_distance|32|cl||
|cl_tree_sway_dir|cmd|cl|sets tree sway wind direction and strength|
|cl_updaterate|128|cl,a,user|Number of packets per second of updates you are requesting from the server|
|cl_updatevisibility|cmd|cl|Updates visibility bits.|
|cl_usercmd_maxcount|4|release|max number of CUserCmds to send in one packet|
|cl_viewtarget_clamp|true|cl||
|cl_voice_transmit_lobby|false|cl,a||
|cl_voiceenabled|true|cl||
|cl_vprof_scope_entity_gamephys|false|cl||
|cl_weather|0|cl,cheat||
|cl_yawspeed|210|cl||
|clear|cmd|norecord,release|Clear console output.|
|clearall|cmd|norecord,release|Clear console output from all views.|
|cli_ent_attachments|cmd|cl,cheat|Displays the interpolated attachment points on an entity.  Arguments|
|cli_ent_hitbox|cmd|cl,cheat|Displays the skeleton for the given entity(ies).  Arguments|
|cli_ent_pivot|cmd|cl,cheat|Displays the interpolated pivot for the given entity(ies).  (y=up=green, z=forward=blue, x=left=red).   Arguments|
|cli_ent_skeleton|cmd|cl,cheat|Displays the skeleton for the given entity(ies).  Arguments|
|cli_ent_vcollide_wireframe|cmd|cl,cheat|Displays the interpolated vcollide wireframe pm am entity.  Arguments|
|client_metrics_upload_batch_seconds|300|cl||
|clientport|0|release|If non-zero, client binds port to specific address.  Usually you should leave this blank to use a different random system-assigned port for each connection.|
|closecaption|true|cl,a,user|Enable close captioning.|
|cloth_approximate_collide|true|||
|cloth_batch|32|||
|cloth_damping_bias|0|||
|cloth_damping_multiplier|1|||
|cloth_debug|0|||
|cloth_debug_draw|0|cl||
|cloth_debug_draw_nodepth_alpha|16|||
|cloth_dry_drag|0|||
|cloth_dry_drag_soften|1|||
|cloth_ground_offset|0|||
|cloth_ground_plane_thickness|3|||
|cloth_guard_threshold|1000|||
|cloth_interpolation_strategy|0|||
|cloth_iv_dump|4|cl||
|cloth_iv_store_back|false|sv,cl,rep||
|cloth_legacy_stretch_force|0.95|||
|cloth_legacy_support|1|||
|cloth_max_ticks_per_frame|8|||
|cloth_node_debug_axis_length|1|||
|cloth_quad_smooth_iterations|-1|||
|cloth_quad_smooth_rate|-1|||
|cloth_quasistatic_iters|0|||
|cloth_reload_immediately|false|||
|cloth_resim_after|0.5|||
|cloth_rigid_update|false|||
|cloth_rod_smooth_iterations|-1|||
|cloth_rod_smooth_rate|-1|||
|cloth_sim_on_tick|true|cl||
|cloth_simulate|true|||
|cloth_sleep_threshold|30|||
|cloth_step|1|||
|cloth_step_variability|0.05|||
|cloth_update|true|cl||
|cloth_update_bones_on_ticks|true|cl||
|cloth_watch|1|rep||
|cloth_wind|0|||
|cloth_wind_pitch|0|||
|cmd|cmd||Forward command to server.|
|cojob_lock_hold_warning_threshold_ms|10000|sv,cl,rep|How long in milliseconds before we warn about lock hold duration|
|cojob_max_no_yield_time_us|3000|sv,cl,rep|Will spew if a job takes longer than the specified number of microseconds|
|col_viz|cmd|sv,rep|Collision visualizer commands|
|collect_entity_model_name|cmd|sv,cheat|Collect model names of the entities you're pointing at|
|commandtool_exec|cmd|sv|Runs a command from the command tool|
|commentary|false|sv,a|Desired commentary mode state.|
|commentary_available|false|sv|Automatically set by the game when a commentary file is available for the current map.|
|commentary_cvarsnotchanging|cmd|sv||
|commentary_finishnode|cmd|sv||
|commentary_node_use_viewfacing|false|cl||
|con_enable|true|a,per_user|Allows the console to be activated.|
|con_logfile_suffix|0||Suffix to append to the console log, may be changed to reopen the log|
|condump|cmd|release|dump the text currently in the console to condumpXX.log|
|connect|cmd|release|Connect to a remote server.|
|connect_hltv|cmd|release|Connect to a remote HLTV server.|
|consoletool|cmd|norecord,release|Open a VConsole subtool.|
|convars_echo_toggle_changes|true||Echo to the console changes caused by toggling.|
|convert_steamid|cmd|cl|Convert SteamID into multiple formats|
|cpu_level|2|cl|CPU Level - Default|
|cpuinfo|cmd||Print CPU configuration information|
|cq_debug|0|sv,rep|Verbose command queue logging.|
|cq_dilation_percentage|5|sv,cl,rep|When speeding up slowing down, this is how much|
|cq_enable|false|sv,cl,rep|Run one usercmd per server tick and maintain a buffer.  Client speeds up/slows down it's usercmd tick rate to maintain server command queue buffering.|
|crash|cmd|cheat|Crash the client. Optional parameter -- type of crash|
|crash_error|cmd|cheat|Cause the engine to crash by Plat_FatalError on main thread (Debug!!)|
|crash_error_job|cmd|cheat|Cause the engine to crash by Plat_FatalError on job thread (Debug!!)|
|crash_error_thread|cmd|cheat|Cause the engine to crash by Plat_FatalError on non-main thread (Debug!!)|
|crash_job|cmd|cheat|Cause the engine to crash in a job thread (Debug!!)|
|crash_thread|cmd|cheat|Cause the engine to crash in a brand new non-main thread (Debug!!)|
|create_flashlight|cmd|sv,cheat||
|creditsdone|cmd|sv||
|crowbar_impact_damage_mass|8|sv||
|crowbar_impact_damage_scale|1|sv||
|csm_bias_override_0|1|cheat||
|csm_bias_override_1|1|cheat||
|csm_bias_override_2|1|cheat||
|csm_bias_override_3|1|cheat||
|csm_cascade0_override_dist|-1|cheat||
|csm_cascade1_override_dist|-1|cheat||
|csm_cascade2_override_dist|-1|cheat||
|csm_cascade3_override_dist|-1|cheat||
|csm_cascade_viewdir_shadow_bias_scale|2|cheat||
|csm_max_num_cascades_override|-1||Number of cascades in sunlight shadow|
|csm_max_shadow_dist_override|-1|||
|csm_res_override_0|0|cheat||
|csm_res_override_1|0|cheat||
|csm_res_override_2|0|cheat||
|csm_res_override_3|0|cheat||
|csm_slope_scale_db_override|-1|cheat||
|csm_split_log_scalar|0.85|cheat||
|csm_viewdir_shadow_bias|0|cheat||
|csm_viewmodel_farz|30|cheat||
|csm_viewmodel_max_shadow_dist|21|cheat||
|csm_viewmodel_max_visible_dist|1000|cheat||
|csm_viewmodel_shadows|false|||
|custom_game_detail_max_friend_lobbies|3|cl|Max number of friend lobbies shown on custom game detail page.|
|custom_game_lobby_fake_entries|0|cl|Add fake entries to the custom lobby UI|
|custom_game_overview_fake_friend_lobbies|0|cl|Fake friend lobbies in custom game overview UI.|
|custom_game_overview_fake_friends_in_game|0|cl|Fake friends in custom game overview UI.|
|custom_game_overview_friend_lobbies_to_hide_ingame_friends|4|cl|When there are this many friend lobbies, the friends ingame display is hidden.|
|custom_game_overview_max_friend_lobbies|3|cl|Max number of friend lobbies shown in custom game overview UI.|
|custom_game_overview_suppress_friend_data|false|cl|Suppress friend active and historical data on custom game overview UI|
|customgamesetup_auto_assign_players|cmd|sv|Automatically assign all curently unassigned player to teams.|
|customgamesetup_enable_auto_launch|cmd|sv|Enable or disable automatically launching the game when all players are assigned to a team.|
|customgamesetup_lock_team_selection|cmd|sv|Lock or unlock the team selection, when locked players cannot change teams.|
|customgamesetup_select_team|cmd|sv|Player selecting a team during custom game setup.|
|customgamesetup_set_auto_launch_delay|cmd|sv|Set the amount of time in seconds that will be set as the remaining time when all players are assigned to a team.|
|customgamesetup_set_remaining_time|cmd|sv|Set the number of seconds remaining before the game starts.|
|customgamesetup_shuffle_players|cmd|sv|Shuffle the team assignments of all players currently assigned to a team.|
|cvarlist|cmd|release|Show the list of convars/concommands.|
|cyclevar|cmd|norecord,release|Cycle through specified convar values.|
|d3d_max_feature_level|11_1||Report the maximum D3D feature level available.|
|dbghist_addline|cmd|sv|Add a line to the debug history. Format|
|dbghist_dump|cmd|sv|Dump the debug history to the console. Format|
|debug_overlay_fullposition|false|sv||
|debug_physimpact|false|sv||
|debug_shared_random|false|sv,cl,rep||
|debug_takedamage_summaries|false|sv,cheat||
|debug_visibility_monitor|0|sv,cheat||
|debugoverlay_cycle_domain|cmd|sv,cheat|Toggles visibility of the debug overlay system.|
|debugoverlay_cycle_state|cmd|sv,cheat|Toggles visibility of the debug overlay system.|
|debugoverlay_draw_current|false|cheat|Tell debugoverlay to not draw any entries that have aged out by the time of rendering. Useful if sim runs more often than rendering.|
|debugoverlay_force_respect_ttl|false|cheat|Force respect TTL even when clearing scopes|
|debugoverlay_hide_imgui|cmd|sv,cheat|Hides the overlay.|
|debugoverlay_ignore_source|false|cheat|Draw everything normal and ignore the source for rendering|
|debugoverlay_show_text_outline|false|cheat|Toggle display of box around text|
|debugoverlay_toggle|cmd|sv,cheat|Toggles visibility of the debug overlay system.|
|decalfrequency|10|sv,nf||
|default_fov|75|cl,cheat||
|demo_allow_game_mismatch|false||Allow playback of demo even if game directories are not matched [may crash or fail to load].|
|demo_flush|false|a|Flush writing the demo file every network update|
|demo_goto|cmd|release|Skips to location in demo.|
|demo_gotomark|cmd|release|Skips the current demo playback to the marked tick|
|demo_gototick|cmd|release|Skips to a tick in demo.|
|demo_info|cmd|release|Print information about currently playing demo.|
|demo_marktick|cmd|release|Marks the current demo playback tick for later use|
|demo_pause|cmd|release|Pauses demo playback.|
|demo_pauseatservertick|0||Pauses demo playback at server tick|
|demo_quitafterplayback|false|release|Quits game after demo playback.|
|demo_recordcommands|true|cheat|Record commands typed at console into .dem files.|
|demo_resume|cmd|release|Resumes demo playback.|
|demo_timescale|cmd|release|Sets demo replay speed.|
|demo_togglepause|cmd|release|Toggles demo playback.|
|demo_usefastgoto|true||Use fast frame skipping when available for demo_goto commands.|
|demo_writefullupdate_rate|60||Interval time in seconds to write full updates to demo.|
|demo_writemetafile|cmd|norecord|save current meta file demo_<version>.meta file for use in demo upconversion.|
|demolist|cmd|release|Print demo sequence list.|
|dev_send_gc_message|cmd|cl|<msgid> Send a blank body message with a given ID to gc for routing tests|
|dev_send_gc_message_server|cmd|sv|<msgid> Send a blank body message with a given ID to gc for routing tests|
|dev_show_event_dungeon_leaderboards|cmd|cl|Show the Dungeon event leaderboards|
|dev_simulate_gcdown|cmd|cl|<state> Turn on/off simulated GC communications failure (GC is down in a way that we know it is down)|
|developer|1|release|Set developer message level.|
|diffcheck|true||Activate diffcheck system.|
|diffcheck_playerslot|0|||
|diffcheck_spew|true||Actually show diffcheck results.|
|diffcheck_spew_diff_filter|0||Show diff with matching filter substring only.|
|diffcheck_spew_diff_only|false||Show diff only.|
|differences|cmd|release|Show all convars which are not at their default values (optional restricted to specific flags).|
|diretide2020_gameplay_tip_number|0|cl,a||
|diretide2020_show_game_info|true|cl,a||
|disable_dynamic_prop_loading|false|sv,cheat|If non-zero when a map loads, dynamic props won't be loaded|
|disable_priority_boost|cmd||Disable focus based priority boost|
|disconnect|cmd|release|Disconnect from server|
|display_game_events|false|sv,cheat||
|dlight_debug|cmd|cl,cheat|Creates a dlight in front of the player|
|dota_1v1_skip_strategy|false|sv,cl,rep||
|dota_aa_test_reduce_playtime_remaining|cmd|cl|Limit available remaining playtime.  Requires -antiaddiction_test.|
|dota_ability_autocast|cmd|cl||
|dota_ability_debug|true|sv,cheat||
|dota_ability_draft_force_gamemode_flag|false|sv,cl,rep,cheat||
|dota_ability_draft_shuffle_players|true|cl,a||
|dota_ability_dump_refcounts|cmd|sv|Dumps the modifier refcounts of all hero abilities|
|dota_ability_execute|cmd|cl||
|dota_ability_learn_mode|cmd|cl|Enter the mode where ability points can be spent|
|dota_ability_legacy_mode_quick_cast|false|cl,a,per_user|Enables quickcast for legacy keys.|
|dota_ability_projection_data_file|scripts/ability_projection.txt|cl,a||
|dota_ability_quick_cast|true|cl,a,per_user||
|dota_ability_quickcast|cmd|cl||
|dota_ability_refcount_modifiers|false|sv,cheat||
|dota_ability_self_cast_timeout|0.6|cl,a,per_user||
|dota_ability_think_always|false|sv||
|dota_activate_window_on_hero_picking_start|false|cl,a|If set, brings Dota to the foreground when hero picking starts|
|dota_activate_window_on_match_found|false|cl,a|If set, brings Dota to the foreground when match found|
|dota_activate_window_on_ready_check|false|cl,a|If set, brings Dota to the foreground on a ready check|
|dota_activate_window_on_unpause|false|cl,a|If set, brings Dota to the foreground when unpaused|
|dota_active_play_section_new|0|cl,a,per_user||
|dota_aghanims_pudge_fx|particles/items2_fx/mask_of_madness.vpcf|sv,cl,rep,cheat||
|dota_aghanims_pudge_fx_overhead|false|sv,cl,rep,cheat||
|dota_aghanims_pudge_fx_sound|DOTA_Item.MaskOfMadness.Activate|sv,cl,rep,cheat||
|dota_aghsfort_watch_tower_allow_completion|true|sv||
|dota_alarm_ring_size|23|cl||
|dota_all_sets_animated|false|cl|Show set tiles always as animated unless high quality dashboard is off.|
|dota_all_vision|false|sv,cl,rep,cheat||
|dota_allow_clientside_entities|true|cl||
|dota_allow_clientside_particles|true|cl||
|dota_allow_invalid_orders|false|cl,cheat||
|dota_allow_orders_multiple_nextbot_updates|true|sv||
|dota_allow_orders_while_paused|false|sv,cheat||
|dota_allow_pause_in_match|true|sv|Allow players to pause in matchmade games|
|dota_alt_show_lane_creep_gold_bounty|true|cl,a||
|dota_alt_show_neutral_creep_gold_bounty|true|cl,a||
|dota_alt_show_neutral_stack_times_and_arrow|true|cl,a||
|dota_alt_show_rune_spawn_times|true|cl,a||
|dota_alt_show_ward_suggestions|true|cl,a||
|dota_alt_shows_neutral_spawn_boxes|true|cl,a,per_user||
|dota_alt_shows_tower_attack_range|true|cl,a,per_user||
|dota_always_show_hero_finder|false|cl,a,per_user|Always display the hero finder.|
|dota_ambient_cloth|false|cl||
|dota_ambient_creatures|false|cl||
|dota_ambient_creatures_pop|false|cl||
|dota_animation_force_modifier|0|sv,cl,rep||
|dota_animation_run|cmd|sv||
|dota_announcer_idle_speech_deathwait|45|sv,cheat|This many seconds must pass after a hero dies for an announcer to consider saying idle lines.|
|dota_announcer_idle_speech_debug|false|sv,cheat|If true print debug information about why announcers do or do not idle.|
|dota_announcer_idle_speech_herodamage_limit|250|sv,cheat|If any hero has taken more than this many hitpoints of damage recently, no idles play.|
|dota_announcer_idle_speech_herodamage_window|45|sv,cheat|If any hero has taken more than dota_announcer_idle_speech_herodamage_limit hitpoints of damage in this many seconds, no idles play.|
|dota_announcer_idle_speech_interval|240|sv,cheat|After an announcer has said an idle line, another can't play for at least this many seconds.|
|dota_announcer_idle_speech_minwait|20|sv,cheat|Announcers won't say idle speech unless at least this many seconds passed since the last time they said something.|
|dota_announcer_idle_speech_starttime|240|sv,cheat|This many seconds must have passed since start of game before announcers poll for idle speech.|
|dota_anonymous_mode|false|cl,a,per_user|If set, you won't see other people's persona names, guild names or avatars|
|dota_apm|cmd|cl||
|dota_apm_update_interval|5|sv,cheat||
|dota_arcana_disable_hud_display|false|cl,a||
|dota_arcana_votes_cache_duration|300|cl||
|dota_armory_all_items_group_by_type|false|cl,a||
|dota_armory_all_items_sort_option|0|cl,a||
|dota_armory_automatically_add_new_item_to_collection|false|cl,a,per_user||
|dota_armory_CustomTagDisplayName_1|Tag1|cl,a||
|dota_armory_CustomTagDisplayName_2|Tag2|cl,a||
|dota_armory_CustomTagDisplayName_3|Tag3|cl,a||
|dota_armory_CustomTagDisplayName_4|Tag4|cl,a||
|dota_armory_CustomTagDisplayName_5|Tag5|cl,a||
|dota_armory_CustomTagDisplayName_6|Tag6|cl,a||
|dota_armory_CustomTagDisplayName_7|Tag7|cl,a||
|dota_armory_CustomTagDisplayName_8|Tag8|cl,a||
|dota_armory_last_selected_hero_id|13|cl,a||
|dota_armory_stickers_group_option|0|cl,a||
|dota_armory_stickers_quality_filter_option|3|cl,a||
|dota_armory_stickers_quality_type_option|0|cl,a||
|dota_assisted_camera_operator_pure_interp_multiplier|16|cl||
|dota_attack_timer_buffer_ticks|3|sv,cheat||
|dota_auto_connect|0|cl|Automatically connect to the specified server forever|
|dota_auto_create_proxy|false|cl|Automatically create a proxy|
|dota_auto_surrender_all_disconnected_timeout|60|sv,cheat|If all players have been disconnected for at least N seconds, end the game immediately|
|dota_autoselect_bots|false|cl,cheat|If set, new bots will be autoselected. This is for the item icon editor.|
|dota_autoselect_entity|none|cl,cheat|If set, new bots of the given type will be autoselected. This is for the item icon editor.|
|dota_battlereport_aggregate_hero_stats_cache_duration|86400|cl||
|dota_bingo_points_animation_duration_max_change|20000|cl||
|dota_bingo_points_animation_duration_max_seconds|5|cl||
|dota_bingo_points_animation_duration_min|0.5|cl||
|dota_bingo_points_animation_duration_min_change|500|cl||
|dota_bloodstone_aoe_size|0|sv,cl,rep,cheat|Size of the bloodstone AOE increase.|
|dota_bot_allow_human_control|false|sv,cheat||
|dota_bot_avg_fps|cmd|sv|Reports the average fps for this dota game|
|dota_bot_chat_throttle_duration|4|sv||
|dota_bot_client_debug|false|cl|Draw some basic client-side debug info for each hero.|
|dota_bot_debug_clear|cmd|sv,cheat|Disables all bot debugging.|
|dota_bot_debug_clear_all|cmd|sv,cheat|Disables all bot debugging.|
|dota_bot_debug_grid|0|sv||
|dota_bot_debug_grid_cycle|cmd|sv,cheat|Cycles through grid modes.|
|dota_bot_debug_lanes|0|sv||
|dota_bot_debug_minimap|0|sv||
|dota_bot_debug_minimap_cycle|cmd|sv,cheat|Cycles through different minimap debug modes.|
|dota_bot_debug_path|false|sv,cheat||
|dota_bot_debug_path_avg|false|sv,cheat||
|dota_bot_debug_path_draw|false|sv,cheat||
|dota_bot_debug_pathing|false|sv||
|dota_bot_debug_potential_location|0|sv||
|dota_bot_debug_team|0|sv,cl,rep||
|dota_bot_debug_team_power|true|cl||
|dota_bot_debug_ward_spots|0|sv||
|dota_bot_difficulty_mask|30|cl,a,per_user|Difficulties of bots to matchmake for.|
|dota_bot_disable|true|sv,cheat||
|dota_bot_disable_test|0|sv||
|dota_bot_disconnect_player|cmd|sv,cheat|Disconnects the player owner of all bots|
|dota_bot_dump_state|cmd|sv|Dumps the entire bot state to the client|
|dota_bot_failed_pathfind_warnings|false|sv,cheat||
|dota_bot_force_pick|0|sv|Force bots to pick one of these heroes before falling back to random selection (should be a comma-separated list with no spaces)|
|dota_bot_force_pick_slot|0|sv|Force picks to be mapped to specific player ids.|
|dota_bot_give_gold|cmd|sv,cheat|Gives all bots the specified amount of gold.|
|dota_bot_give_item|cmd|sv|Creates an item for all bots.|
|dota_bot_give_level|cmd|sv|Gives all bots the specified number of levels.|
|dota_bot_level|0|sv|If set, bots will be set to the level specified with appropriate gold on game start|
|dota_bot_long_frame_limit|2|sv,a||
|dota_bot_match_solo|false|cl,a||
|dota_bot_mode|true|sv,cl,rep||
|dota_bot_populate|cmd|sv|Populates the remaining slots with bots|
|dota_bot_populate_seeded|cmd|sv|Populates the remaining slots with hard bots given a random seed|
|dota_bot_potential_debug|cmd|sv,cheat|Displays potential locations for this bot.|
|dota_bot_practice_difficulty|3|sv,cl,rep|Default difficulty for quick bot practice games|
|dota_bot_practice_gamemode|1|sv,cl,rep|Default game mode for bot practice games, AP = 1|
|dota_bot_practice_script|0|sv,cl,rep|Bot script ID to use for local games.|
|dota_bot_practice_select_hero|0|sv,cl,rep|Force selection of a hero for the human player in practice games.|
|dota_bot_practice_start|false|sv,cl,rep|Whether to start a local game when the map loads|
|dota_bot_practice_team|0|sv,cl,a,rep|Default team for quick bot practice games|
|dota_bot_practice_team_desired|0|cl,a||
|dota_bot_purchase_item_enable|true|sv||
|dota_bot_reload_scripts|cmd|sv|Reloads all the bot scripts|
|dota_bot_script_index_mask|15|cl,a,per_user|Valid dedicated server script indexes for bots.|
|dota_bot_select_debug|cmd|sv,cheat|Displays general bot debugging information.|
|dota_bot_select_debug_attack|cmd|sv,cheat|Displays debugging info on potential attack targets.|
|dota_bot_set_difficulty|cmd|sv,cheat|Sets all bots to a particular difficulty (0 = easy, 1 = medium, 2 = hard, 3 = unfair.|
|dota_bot_spam_modes|false|sv||
|dota_bot_takeover_disconnected|false|sv,cheat||
|dota_bot_tutorial_boss|true|sv||
|dota_bot_use_machine_learned_weights|true|sv||
|dota_bp_frontpage_takeover_test_live_matches|cmd|cl|Setup the frontpage takeover with some match data things.|
|dota_bp_team_fandom_last_seen|1695243600|cl,a||
|dota_broadcast_is_live_cache_duration_s|15|cl||
|dota_broadcaster_camera_interp|0.8|cl||
|dota_broadcaster_channel_country_name|0|cl,a|Broadcaster Channel Country Name|
|dota_broadcaster_channel_description|0|cl,a|Broadcaster Channel Description|
|dota_broadcaster_channel_language|0|cl,a|Broadcaster Channel Language|
|dota_broadcaster_channel_save_settings|true|cl,a||
|dota_broadcaster_dismiss_all_stats|cmd|cl||
|dota_building_defended_radius|800|sv,cheat||
|dota_building_health_loss_warn_interval|9|sv,cheat|Minimum seconds between announcer warning a particular building is under attack|
|dota_cache_duration_all_hero_challenge_s|1800|cl||
|dota_cache_duration_bingo_league_stats_s|3|cl||
|dota_cache_duration_coach_history_s|300|cl||
|dota_cache_duration_custom_game_counts_s|300|cl||
|dota_cache_duration_favoriteplayers_s|14400|cl||
|dota_cache_duration_guild_data_s|900|cl||
|dota_cache_duration_guild_persona_data_s|10800|cl||
|dota_cache_duration_guild_summary_s|300|cl||
|dota_cache_duration_leaderboard_s|60|cl||
|dota_cache_duration_league_admin_list_s|30|cl||
|dota_cache_duration_league_dpc_standings_s|60|cl||
|dota_cache_duration_league_info_s|30|cl||
|dota_cache_duration_league_list_s|600|cl||
|dota_cache_duration_league_live_dpc_games_s|30|cl||
|dota_cache_duration_league_live_games_s|5|cl||
|dota_cache_duration_league_lobby_nodes_s|5|cl||
|dota_cache_duration_league_node_results_s|5|cl||
|dota_cache_duration_league_prediction_results_s|5|cl||
|dota_cache_duration_league_predictions_s|60|cl||
|dota_cache_duration_league_prize_pool_s|5|cl||
|dota_cache_duration_limited_item_purchase_s|1800|cl||
|dota_cache_duration_partysearch_s|10|cl||
|dota_cache_duration_player_accomplishments_s|300|cl||
|dota_cache_duration_team_info_s|60|cl||
|dota_camera_accelerate|0|cl,a,per_user||
|dota_camera_allow_freecam|false|cl,cheat||
|dota_camera_assisted_camera_operator_bias_constant_oneteam|1|cl||
|dota_camera_assisted_camera_operator_bias_constant_twoteams|0.1|cl||
|dota_camera_assisted_camera_operator_bias_frame_multiplier|1|cl||
|dota_camera_assisted_camera_operator_bias_scale|1.4|cl||
|dota_camera_assisted_camera_operator_bias_scale_frame_multiplier|0.5|cl||
|dota_camera_assisted_camera_operator_blend_multiplier|1.5|cl||
|dota_camera_assisted_camera_operator_inner_radius_at_zoomed_in|250|cl||
|dota_camera_assisted_camera_operator_input_cooldown|0.5|cl||
|dota_camera_assisted_camera_operator_interp_speed_bias_param|0.5|cl||
|dota_camera_assisted_camera_operator_interp_speed_dist_max|8000|cl||
|dota_camera_assisted_camera_operator_interp_speed_dist_min|500|cl||
|dota_camera_assisted_camera_operator_interp_speed_multiplier|1.5|cl||
|dota_camera_assisted_camera_operator_interp_speed_speed_max|50|cl||
|dota_camera_assisted_camera_operator_interp_speed_speed_min|1.5|cl||
|dota_camera_assisted_camera_operator_max_instanteous_ent_velocity|275|cl||
|dota_camera_assisted_camera_operator_mouseclick_duration|0.1|cl||
|dota_camera_assisted_camera_operator_movement_multiplier|2400|cl||
|dota_camera_assisted_camera_operator_null_zone_enabled|true|cl||
|dota_camera_assisted_camera_operator_null_zone_velocity_max|125|cl||
|dota_camera_assisted_camera_operator_null_zone_velocity_min|100|cl||
|dota_camera_assisted_camera_operator_outer_radius_at_zoomed_in|600|cl||
|dota_camera_assisted_camera_operator_pan_movement_interp_multiplier_in|20|cl||
|dota_camera_assisted_camera_operator_pan_movement_interp_multiplier_out|6|cl||
|dota_camera_assisted_camera_operator_radius_scale_at_zoomed_out|4|cl||
|dota_camera_assisted_camera_operator_unit_fade_duration|1.5|cl||
|dota_camera_broadcaster_mousewheel_direction_multiplier|0.025|cl|Multiplier on direction, used for broadcasters only.|
|dota_camera_broadcaster_mousewheel_frametime_multiplier|1|cl|Multipler on frametime, used for broadcasters only.|
|dota_camera_center|cmd|cl||
|dota_camera_center_on_entity|cmd|cl||
|+dota_camera_center_on_hero|cmd|cl||
|dota_camera_deatheffect|false|cl,a,per_user||
|dota_camera_disable_yaw|true|cl,cheat||
|dota_camera_disable_zoom|true|cl,a,per_user||
|dota_camera_distance|1200|cl,cheat||
|dota_camera_distance_min|1134|cl,cheat||
|dota_camera_distance_teamspec|2600|cl,cheat||
|dota_camera_dotatv_smooth_drag|false|cl,a,per_user||
|dota_camera_dotatv_smooth_drag_drag|0.075|cl||
|dota_camera_dotatv_smooth_drag_inverse|false|cl||
|dota_camera_dotatv_smooth_drag_max_speed|25|cl||
|dota_camera_drag_factor_zoomed_out|0.5|cl,cheat||
|dota_camera_edgemove|false|cl,a,user||
|dota_camera_focus_player|cmd|cl||
|dota_camera_fog_end_scalar|1|cl,cheat||
|dota_camera_fog_end_zoomed_in|2500|cl,cheat||
|dota_camera_fog_end_zoomed_out|6000|cl,cheat||
|dota_camera_fog_start_scalar|1|cl,cheat||
|dota_camera_fog_start_zoomed_in|2000|cl,cheat||
|dota_camera_fog_start_zoomed_out|4500|cl,cheat||
|+dota_camera_follow|cmd|cl||
|dota_camera_follow_doublepress_time|0.5|cl||
|dota_camera_get_lookatpos|cmd|cl|Prints the main camera's look-at position.|
|dota_camera_get_pos|cmd|cl|Prints the camera position. If you are trying to set DOTA's main camera position, you probably want to use dota_camera_get_lookatpos and dota_camera_set_lookatpos.|
|dota_camera_hero_inspector_bob_amount|0.2|cl||
|dota_camera_hero_inspector_camera_height_percentage|0.5|cl|% of the hero's hitbox height.|
|dota_camera_hero_inspector_camera_lookat_height_percentage|0.5|cl|% of the hero's hitbox height.|
|dota_camera_hero_inspector_dist_max|1000|cl||
|dota_camera_hero_inspector_dist_min|150|cl||
|dota_camera_hero_inspector_drag_scale|1|cl||
|dota_camera_hero_inspector_drag_speed_const|25|cl||
|dota_camera_hero_inspector_drag_yaw_max|89|cl||
|dota_camera_hero_inspector_drag_yaw_min|-60|cl||
|dota_camera_hero_inspector_duration|0.75|cl||
|dota_camera_hero_inspector_fog_end_max|4000|cl||
|dota_camera_hero_inspector_fog_end_min|4000|cl||
|dota_camera_hero_inspector_fog_start_max|1200|cl||
|dota_camera_hero_inspector_fog_start_min|500|cl||
|dota_camera_hero_inspector_fov_buffer_multiplier|1.25|cl||
|dota_camera_hero_inspector_fov_default|75|cl||
|dota_camera_hero_inspector_fov_max|80|cl||
|dota_camera_hero_inspector_fov_min|50|cl||
|dota_camera_hero_inspector_grass_skew_multiplier|0.33|cl||
|dota_camera_hero_inspector_mousewheel_direction_multiplier|0.05|cl||
|dota_camera_hero_inspector_mousewheel_frametime_multiplier|2|cl||
|dota_camera_hero_inspector_mousewheel_process_interval|0.1|cl||
|dota_camera_hero_inspector_speed_const|4|cl||
|dota_camera_hero_inspector_use_third_person|false|cl|Locks the showcase behind the hero|
|dota_camera_hero_inspector_zfar_max|4000|cl||
|dota_camera_hero_inspector_zfar_min|3500|cl||
|dota_camera_hold_select_to_follow|false|cl,a|If set, pressing the select hero button will actively follow and keep you on screen|
|dota_camera_legacy|0|cl,a|Use old settings for Dota camera.|
|dota_camera_legacy_enabled|true|sv,cl,rep||
|dota_camera_lerp_duration|2|cl||
|dota_camera_lerp_position|cmd|cl|Blend the camera lookat position.|
|dota_camera_lock|false|cl||
|dota_camera_lock_lerp|0|cl,a||
|dota_camera_lock_mouse_lead|220|cl||
|dota_camera_lock_view_helper|true|cl||
|dota_camera_lock_view_helper_ratio|0.45|cl||
|dota_camera_mousewheel_delay_reset_interval|1|cl|The mousewheel delay timer is reset after this interval. Does not apply to spectator zooming.|
|dota_camera_mousewheel_direction_multiplier|0.03|cl|Multiplier on direction|
|dota_camera_mousewheel_start_delay|0.1|cl|The delay (in seconds) before mousewheeling will begin to actually zoom. Only used for players in-game. Does not apply to spectator zooming.|
|dota_camera_reverse|false|cl,a,per_user||
|dota_camera_saved_position|cmd|cl||
|dota_camera_set_lookatpos|cmd|cl|Sets the main camera's look-at position from (x,y) coordinates.|
|dota_camera_set_position|cmd|cl|Set the camera lookat position.|
|dota_camera_smart_follow_drag_distance|500|cl||
|dota_camera_smart_follow_edge_distance|500|cl||
|dota_camera_smart_follow_offset_reset|8|cl||
|dota_camera_smart_follow_offset_time|1|cl||
|dota_camera_smooth_count|8|cl||
|dota_camera_smooth_distance|96|cl||
|dota_camera_speed|3082.76|cl,a,per_user||
|dota_camera_stage_fov|15|cl||
|dota_camera_stage_pitch|0|cl||
|dota_camera_stage_rotate|0|cl||
|dota_camera_stage_x|25|cl||
|dota_camera_stage_y|-600|cl||
|dota_camera_stage_yaw|90|cl||
|dota_camera_stage_z|225|cl||
|dota_camera_temporary_freecamera_time|2.5|cl||
|dota_camera_terrain_sample_timer_duration|0.1|cl||
|dota_camera_yaw_rotate_hold_time|1|cl||
|dota_camera_yaw_rotate_speed|0.2|cl||
|dota_camera_z_interp_speed|10|cl||
|dota_camera_zfar_zoomed_in|3300|cl,cheat||
|dota_camera_zfar_zoomed_out|4800|cl,cheat||
|dota_camera_zoom_return_to_default_speed|0.001|cl,cheat||
|dota_camera_zoom_return_to_default_time|30|cl,cheat||
|dota_camera_zoom_return_to_default_time_spectator_enabled|true|cl||
|dota_cameraman_queryunit_slave|0|cl|Query unit controls for camera man.  0=none, 1=copy main broadcaster query unit, but allow local override, 2=always slave from main broadcaster, no local control over query unit|
|dota_cancel_GG|cmd|sv|Cancel GG call|
|dota_candy_shop_generate_recipes|cmd|cl|Generate 4 recipes.|
|dota_candy_shop_print_recipes|cmd|cl|Generate all recipes.|
|dota_cd_captain_pick_time|10|sv,cheat||
|dota_cd_minimum_pick_time|5|sv,cheat||
|dota_chat_allow_global|true|cl,a,per_user|Allow chat channels to be set to global, causing their chat to show up in other channel's tabs.|
|dota_chat_broadcast_whispers|true|cl,a|Show whispers in all chat tabs, not just the tab for the individual user.|
|dota_chat_disable_refresh_user_list|false|cl||
|dota_chat_enable_whispers|true|cl,a,per_user|Show steam messages as whispers inline in chat.|
|dota_chat_filter_settings|3|cl,a|What chat filtering level the user wants (EDotaChatFilter)|
|dota_chat_filter_settings_apply_to_spectators|false|cl,a|Whether chat filtering applies to spectating as well or not.|
|dota_chat_lines_always_create_new_label|false|cl||
|dota_chat_scroll_step|10|cl||
|dota_cheap_water|true|cl||
|dota_check_localization|cmd|cl|Look over unit and ability data to verify that all the expected localization strings are present|
|dota_cheers_enable_scene_reload|false|cl,a||
|dota_cl_projection_enabled|true|cl||
|dota_claim_item_action_async_rewards_timeout_duration|20|cl||
|dota_client_filesystem_warnings|false|cl|Set fs_warning_level and fs_warning_mode to warn on synchronous file warnings.|
|dota_client_first_session|false|cl,a,per_user||
|dota_clip_builder_bitrate|30|cl,a,per_user|Bitrate of the resulting clip|
|dota_clip_builder_format|mp4|cl,a,per_user||
|dota_clip_builder_framerate|60|cl,a,per_user||
|dota_clip_builder_hide_game_ui|false|cl,a,per_user||
|dota_clip_builder_high_quality_rendering|true|cl,a,per_user||
|dota_clip_builder_max_duration|60|cl,a,per_user||
|dota_clip_builder_output_folder|0|cl,a,per_user||
|dota_clip_builder_seconds_graduation|1|cl,a,per_user||
|dota_clip_unreachable_paths|true|sv||
|dota_cm_captain_pick_time|10|sv,cheat||
|dota_cm_minimum_pick_time|5|sv,cheat||
|dota_collapsed_bundled_item_list|false|cl,a,per_user||
|dota_collapsed_new_item_list|false|cl,a,per_user||
|dota_collapsed_recent_item_list|false|cl,a,per_user||
|dota_collections_stack_duplicates|false|cl,a||
|dota_combat_log_update_interval|1|cl,cheat||
|dota_combatlog_fight_idle_time|5|sv,cl,rep|The amount of time needed to determine a fight is over (no one involved in a fight did anything to anyone else involved in the fight).|
|dota_combatlog_file|0|cl|A file you want to write combatlog events to as they happen.|
|dota_combatlog_location_interval|1|sv,cheat||
|dota_combatlog_scan|cmd|cl|Scans for fights|
|dota_combatlog_size|cmd|cl|Calculates the total allocations for a combatlog|
|dota_combatlog_size_server|cmd|sv||
|dota_combatlog_summary|cmd|sv||
|dota_combatlog_update|cmd|sv|Send combat log to a client|
|dota_combatlog_write_test|cmd|cl|Writes combatlog to disk if you have dota_combatlog_file set|
|dota_combine_models|true|cl,rep||
|dota_commander_report|cmd|sv|Prints a snapshot of the commander's state|
|dota_competitive_game_modes|0|cl,a|Bit masks of game modes to search for in ranked matchmaking|
|dota_conduct_scorecard_latest_ack_seq_num|1048|cl,a,per_user|Sequence number of latest conduct summary that has been acknowledged.|
|dota_consumable_portal_reward_close_delay|2.5|sv,cl,rep,cheat||
|dota_consumable_portal_reward_delay_max|3|sv,cl,rep,cheat||
|dota_consumable_portal_reward_delay_min|1.5|sv,cl,rep,cheat||
|dota_contest_schema_do_contest_validation|true|cl||
|dota_context_aware_voice_change_window_minutes|2|sv,cl,rep,cheat||
|dota_context_aware_voice_networth_change_threshold|0.025|sv,cl,rep,cheat||
|dota_context_aware_voice_networth_threshold|0.09|sv,cl,rep,cheat||
|dota_contextual_tips_queue_custom_tip|cmd|cl|Queues a specific custom client tip to be displayed|
|dota_contextual_tips_queue_tip_id|cmd|cl|Queues a specific tip ID to be displayed|
|dota_continue_click_movement_after_cast_cancel|true|cl,a,per_user||
|+dota_control_group|cmd|cl||
|dota_courier_burst|cmd|cl|Activate speed burst on courier|
|dota_courier_deliver|cmd|cl|Order courier to deliver my items|
|dota_courier_shield|cmd|cl|Activate speed shield on courier|
|dota_crate_treasure_use_alt_listview|false|cl,a,per_user||
|dota_create_ability|cmd|sv|Create an ability for the player's hero at the first unused ability index|
|dota_create_bot_wearing_item|cmd|sv,cheat|Creates a bot wearing a given item def index.|
|dota_create_bot_wearing_set|cmd|sv,cheat|Creates a bot wearing a given set of items from a bundle object.|
|dota_create_fake_clients|cmd|sv,cheat|Populates the remaining slots with fake clients|
|dota_create_item|cmd|sv|Creates an item for the selected unit|
|dota_create_neutral_hero|cmd|sv,cheat|Creates an unit|
|dota_create_unit|cmd|sv,vconsole_fuzzy|Creates an unit|
|dota_creep_distance_interval|5|sv||
|dota_creep_stack_nearby_hero_radius|3000|sv||
|dota_creeps_no_spawning|false|sv,cheat||
|dota_custom_game_difficulty_mask|2|cl,a,per_user|Difficulties of the event game to matchmake for.|
|dota_custom_game_library_filter|0|cl,a|Custom game library filter type|
|dota_custom_game_library_sort|0|cl,a|Custom game library sort type|
|dota_custom_game_local_lobbies_max_ping|150|cl,a,per_user|Maximum ping for custom game overview.|
|dota_custom_game_overview_max_lobby_age_seconds|1800|cl,a,per_user|Maximum lobby age to be visible in overview.|
|dota_custom_games_enable_browse_tab|true|cl||
|dota_custom_games_exclude|0|cl|Comma separated list of IDs to exclude from custom games overview page|
|dota_custom_games_overview_sort_mode_mode|1|cl,a,per_user|Sort method used for the custom games overview page|
|dota_custom_ui_debug_panel|cmd|cl|Usage|
|dota_cycle_prev_selected|cmd|cl||
|dota_cycle_selected|cmd|cl||
|dota_damage_flash|true|sv,a|Flash when enemies take damage from the player|
|dota_dashboard_enable_mouse_history|true|cl,a,per_user|Enables Mouse4/Mouse5 to navigate dashboard history.|
|dota_dashboard_force_background|0|cl||
|dota_dashboard_launch_count|987|cl,a,per_user||
|dota_dawnbreaker_attack_combo_cooldown_time|5|sv,cl,rep|Adjust the amount of time the combo animation state persists after an attack starts. Set to -1 to disable attack combos entirely.|
|dota_dawnbreaker_attack_combo_step_time|0.3|sv,cl,rep|We won't advance the combo state faster than this time, so stutter stepping doesn't advance the combo anim.|
|dota_daynightcycle_pause|false|sv,cheat|0 = resume day/night cycle; 1 = pause day/night cycle; default = 0;|
|dota_daynightcycle_toggle|cmd|sv,cheat|Toggle the day-night cycle.|
|dota_db_frontpage_takeover_set_stream|cmd|cl|<control_num> <stream_name> [t1_wins] [t2_wins] Overrides an entry in the list to have specific match data.|
|dota_dead_unit_delete_time|1|sv,cheat||
|dota_dead_unit_disappear_time|4|sv,cheat||
|dota_debug_global_light|0|cl,cheat||
|dota_debug_lasthit_timing|false|sv,cl,rep||
|dota_debug_location_x|0.01|sv||
|dota_debug_location_y|0.01|sv||
|dota_debug_onstage_seats|false|cl||
|dota_debug_so_cache|false|cl|Log SO cache messages|
|dota_debug_stuck|false|sv,cheat||
|dota_debut_movie_volume|0.6|cl||
|dota_default_gold|600|sv,cheat||
|dota_default_spoilers_blocked|false|cl,a,per_user|Avoid spoilers for league matches|
|dota_defer_panorama_on_sim_ticks|true|cl||
|dota_dev|cmd|sv,cheat|DotA dev commands|
|dota_dev_weekend_hub_status|-1|cl||
|dota_director_record_combat_log|1|sv||
|dota_director_shoulder_view_chance|10|sv||
|dota_disable_acknowledged_item_auto_equip|false|cl,a,per_user||
|dota_disable_add_fractional_attack_time|false|sv,cheat||
|dota_disable_attack_regulator|false|sv,cheat||
|dota_disable_autoattack_during_stop|false|cl,a,per_user||
|dota_disable_bot_lane|false|sv,cl,rep||
|dota_disable_controller_support|true|cl||
|dota_disable_experimental_gameplay|false|cl||
|dota_disable_lan_lobby_broadcast|false|cl|Don't send UDP broadcast packets for LAN lobby discovery|
|dota_disable_mid_lane|false|sv,cl,rep||
|dota_disable_particle_lights|false|cl,release|Disable the rendering of particle local lights.|
|dota_disable_showcase_view_button|false|cl|Disable the Showcase View button unless sv_cheats is enabled.|
|dota_disable_top_lane|false|sv,cl,rep||
|dota_disable_unit_ring|false|cl||
|dota_dpc_favorite_teams_cache_duration|600|cl||
|dota_dpc_reset_spoilers|cmd|cl|clear dpc spoiler data|
|dota_draft_trivia_enabled|true|cl||
|dota_draw_portrait|true|cl,cheat||
|dota_draw_simple_selection_box|false|cl,a,per_user||
|dota_drow_ranger_arcana_disable_display|false|cl,a||
|dota_dump_behavior|cmd|cl|Dump Behavior score info.|
|dota_dump_bot_state|cmd|cl||
|dota_dump_buff_message_count|cmd|sv|dota_dump_buff_message_count|
|dota_dump_client_asset_modifiers|cmd|cl,cheat|Dump asset modifiers on the client.|
|dota_dump_connection_stats|cmd|sv|Dump current connection stats|
|dota_dump_creep_stats|cmd|sv,cheat|Displays stats on creep denies/lasthits/kills.|
|dota_dump_game_items|cmd|sv|Print a list of all game items with their item ids in CSV format.|
|dota_dump_hero_history|cmd|sv|Dump items and abilities that a hero has bought/leveled|
|dota_dump_inventory|cmd|cl||
|dota_dump_keybindings|false|cl||
|dota_dump_server_asset_modifiers|cmd|sv,cheat|Dump asset modifiers on the server.|
|dota_dump_server_inventory|cmd|sv||
|dota_dump_units|cmd|sv|Print a list of all game units.|
|dota_earthshaker_arcana_disable_combo_display|false|cl,a||
|dota_easybuy|false|sv,cl,rep,cheat|Everything is free, all shops are in range, and you can purchase for other heroes|
|dota_echoslam_max_projectiles|75|sv,cheat||
|dota_econ_item_animation_speed|0.4|cl|The animation speed of the full set tiles.|
|dota_econ_item_high_market_price_threshold|10000|cl||
|dota_econ_item_immortal_animation_speed|0.2|cl|The animation speed of the immortal item tiles.|
|dota_econ_item_particle_sim_speed|0.7|cl|The simulation speed of particles in full set tiles.|
|dota_effective_creep_spawn_time|0|sv,cheat|If non-zero, the time the creep spawner uses for deciding what to spawn|
|dota_enable_direct_quickcast_bindings|true|cl,a,per_user|Enables ability to directly bind keys to quickcast.|
|dota_enable_illusion_recycling|false|sv||
|dota_enable_new_player_shop|false|cl,a,per_user|Enables simple shop mode|
|dota_enable_range_finder|true|cl,a,per_user||
|dota_enable_same_user_chat_wheel_pitch_increase|false|cl,cheat||
|dota_enable_spatial_audio|false|release|Flag to enable spatial audio in Dota 2.|
|dota_endgame_cinematic_disable|false|sv,cl,rep||
|dota_enemy_color|25500|cl||
|dota_enemy_color_cb|25500|cl||
|dota_entity_count_grace_threshold|128|sv|Number of entities to reserve when we're getting close to the limit. Stops some entities from spawning.|
|dota_event_goal_update_delay|300|cl||
|dota_event_stage|0|sv,cl,rep||
|dota_event_tips_cache_duration|300|cl||
|dota_experimental_enable_particles_named_values|false|sv,cl,rep,cheat||
|dota_experimental_stats_interval|60|sv|Seconds between each experimental stat update.|
|dota_export_steam_inventory_layout|cmd|cl|Save the inventory layout to the Steam servers.|
|dota_export_steam_inventory_layout_flow|cmd|cl|Save the inventory layout to the Steam servers.|
|dota_externalwebapi_debug_leagueid|0|cl|Set this to test the external web API as if the game were a specific league.|
|dota_faceless_void_arcana_disable_display|false|cl,a||
|dota_fake_accept_slots|0|cl||
|dota_fake_announcer_teamid|0|cl||
|dota_fake_battle_cup_live_game|false|cl||
|dota_fake_event_wins|-1|cl||
|dota_fake_event_wins_claimed|-1|cl||
|dota_fake_front_page_cell_top_game|0|cl|Creates fake game data for a top game on the front page cells. 0 = disabled, 1 = regular game, 2 = league game|
|dota_fake_gc_connection_state|-1|cl||
|dota_fake_gc_est_time|-1|cl||
|dota_fake_gc_queue_pos|-1|cl||
|dota_fake_lobby_browser_data|false|cl||
|dota_fake_lobby_count|100|cl||
|dota_fake_no_match_metadata|false|cl||
|dota_fake_role_handicap_hardsupport|-1|cl||
|dota_fake_role_handicap_midlane|-1|cl||
|dota_fake_role_handicap_offlane|-1|cl||
|dota_fake_role_handicap_safelane|-1|cl||
|dota_fake_role_handicap_support|-1|cl||
|dota_fanfare_disable|true|sv||
|dota_fantasy_craft_tutorial_state|127|cl,a||
|dota_fantasy_league_region|1|cl,a,per_user|Set a valid league region.|
|dota_fantasy_popup_help_dpc|false|cl,a||
|dota_fantasy_popup_help_ti10|true|cl,a||
|dota_fantasy_spew_scoring|false|cl,cheat||
|dota_fantasy_stat_update_interval_s|20|sv,cheat|How often the server updates the GC with player fantasy stats|
|dota_featured_game_mode_splash_time|1660934178|cl,a,per_user||
|dota_fight_recap_button_stay_time|35|cl,a||
|dota_fight_recap_terse|false|cl,a||
|dota_flip_home_team|false|cl||
|dota_fog_offset|0|cl||
|dota_force_battle_cup_winner|0|sv,cheat||
|dota_force_bot_cycle|0|sv|Set automatically by matchmaking to fill slots with bots|
|dota_force_default_death_stinger|false|cl,a,per_user||
|dota_force_default_respawn_stinger|false|cl,a,per_user||
|dota_force_gamemode|1|sv,cl,rep|Force the game mode to a specific one. AP = 1, CM = 2, RD = 3, SD = 4. INTRO = 6. 7 = HW. 8 = REVERSE CM. 9 = XMAS|
|dota_force_minigame|0|sv,cl,rep||
|dota_force_neutral_drop_tier|0|sv,rep,cheat||
|dota_force_pick_allow|false|sv,cl,rep||
|dota_force_right_click_attack|2|cl,a,per_user||
|dota_force_rune|-1|sv,rep,cheat|Always spawn the same rune.|
|dota_force_upload_match_stats|false|sv,cheat|If enabled, server will upload match stats even when there aren't human players on each side|
|dota_fountain_idle_minimum_time|0|sv|How long into the game we need to be before we boot players for being intentionally Idle.|
|dota_fow_grid_size|64|sv,cl,rep||
|dota_free_ids|cmd|cl|Shows next free ID for items, abilities and heroes.|
|dota_friendly_color|02550|cl||
|dota_friendly_color_cb|33161255|cl||
|dota_friends_favorites_expanded|true|cl,a|If true expands favorites sub nav, if false minimizes it.|
|dota_friends_friends_playing_expanded|true|cl,a|If true expands friends playing dota sub nav, if false minimizes it.|
|dota_friends_guild_members_expanded|true|cl,a|If true expands guild members sub nav, if false minimizes it.|
|dota_friends_offline_expanded|true|cl,a|If true expands friends online sub nav, if false minimizes it.|
|dota_friends_online_expanded|false|cl,a|If true expands friends online sub nav, if false minimizes it.|
|dota_friends_open_party_expanded|true|cl,a|If true expands open party sub nav, if false minimizes it.|
|dota_friends_pending_expanded|true|cl,a|If true expands friends pending sub nav, if false minimizes it.|
|dota_game_account_client_debug|cmd|cl|Prints game account client info|
|dota_game_account_plus_debug|cmd|cl|Prints game account plus info|
|dota_game_end_match_details_delayed_time|4|cl|After showing game end message, if server hasn't told us it signed out with the GC, then turn on warning text|
|dota_game_end_match_details_time_out|10|cl|Max time client waits for server to let it know that it has signed out with GC.|
|dota_game_end_match_details_time_out_weekend_tourney|60|cl|Max time client waits for server to let it know that it has signed out with GC, in weekend tourney match|
|dota_gamemode_ability_draft_per_player_time|7|sv,cl,rep|Total time in seconds a player has to draft an ability|
|dota_gamemode_ability_draft_pre_round_time|5|sv,cl,rep|Break between rounds|
|dota_gamemode_ability_draft_pre_time|60|sv,cheat||
|dota_gamemode_ability_draft_set_draft_hero_and_team|cmd|cl,cheat,vconsole_fuzzy|Manually select which heroes will be assigned during Ability Draft lobby game. Usage|
|dota_gamemode_ability_draft_set_draft_hero_and_team_clear|cmd|cl,cheat|dota_gamemode_ability_draft_set_draft_hero_and_team |
|dota_gamemode_ardm_hero_count|90|sv,cheat||
|dota_gamemode_ardm_sellback_percent|0.85|sv,cl,rep,cheat||
|dota_gamestate|cmd|sv|Print current game state|
|dota_get_team_info|cmd|cl||
|dota_gg_call_time|10|sv,rep||
|dota_gift_permissions_cache_duration|300|cl||
|dota_gift_permissions_request_timeout|60|cl||
|dota_global_hero_stats_cache_duration|300|cl||
|dota_global_item_shuffle_enabled_slots|64|cl,a,per_user||
|dota_global_item_shuffle_enabled_slots_upconverted|true|cl,a,per_user||
|dota_glyph|cmd|cl|trigger the Glyph of Fortification for your team|
|dota_gold_redistribute_time|1|sv,cheat||
|dota_gold_summary|cmd|cl|Print out gold info|
|dota_graph_player_items_inset|10|cl||
|dota_graph_player_items_min_quality|0|cl||
|dota_graph_player_items_right_margin|100|cl||
|dota_graph_player_items_show_consumables|false|cl||
|dota_greevil_black_essence|-1|sv,cheat||
|dota_greevil_blue_essence|-1|sv,cheat||
|dota_greevil_green_essence|-1|sv,cheat||
|dota_greevil_orange_essence|-1|sv,cheat||
|dota_greevil_purple_essence|-1|sv,cheat||
|dota_greevil_red_essence|-1|sv,cheat||
|dota_greevil_white_essence|-1|sv,cheat||
|dota_greevil_yellow_essence|-1|sv,cheat||
|dota_gridnav_perf_test|cmd|sv||
|dota_gridnav_show|0|sv,cheat||
|dota_gridnav_show_size|1|sv,cheat|Control the size of the gridnav display. 1 = small, 2 = medium, 3 = large|
|dota_grinder_snap_to_damage|false|cl,cheat||
|dota_guide_enable_publish_all|false|cl,a,per_user|Enable publish all feature for guides|
|dota_guide_prioritize_recent|false|cl,a,per_user||
|dota_guild_banner_replacement_radius|0|sv,cl,rep|how far from the fountain to replace banners with guild ones ( < 0|
|dota_guild_details_force_show_chat_type|false|cl||
|dota_guild_ignore_invites|false|cl,a,per_user||
|dota_guild_ignore_nonfriend_invites|false|cl,a,per_user|If set, guild invites from non-friends are automatically rejected|
|dota_guild_persona_batch_interval|0.5|cl||
|dota_guild_persona_use_webapi|false|cl||
|dota_hack_delay_start|false|sv||
|dota_health_bar_pips|true|cl||
|dota_health_bar_shields|true|cl||
|dota_health_bar_threat_height|32|cl||
|dota_health_bar_threat_icons|false|cl||
|dota_health_bar_threat_icons_force_value|-1|cl||
|dota_health_bar_threat_width|32|cl||
|dota_health_bar_threat_y_offset|16|cl||
|dota_health_bar_threat_y_offset_local_user|22.5|cl||
|dota_health_high_marker_major_alpha|128|cl||
|dota_health_high_marker_minor_alpha|0|cl||
|dota_health_high_threshold|15000|cl||
|dota_health_hurt_decay_time_max|0.8|cl||
|dota_health_hurt_decay_time_min|0.3|cl||
|dota_health_hurt_delay|0.1|cl||
|dota_health_hurt_threshold|0.01|cl||
|dota_health_marker_major_alpha|225|cl||
|dota_health_marker_minor_alpha|96|cl||
|dota_health_per_vertical_marker|250|cl|How much health between each vertical line in the health bars|
|dota_height_fog_scale|1|cl,cheat||
|dota_help_tips_active_per_category|2|cl||
|dota_help_tips_enabled|false|cl,a,per_user||
|dota_help_tips_reset|cmd|cl|Removes records of any already dismissed help tips.|
|dota_help_tips_reset_intro|cmd|cl|Removes records of intro tips.|
|dota_hero_adjectives_dump|cmd|cl|[adjective] [value] Dumps out which heroes have which adjectives|
|dota_hero_auto_graball|false|cl||
|dota_hero_demo_default_enemy|npc_dota_hero_bloodseeker|cl,a||
|dota_hero_demo_spawn_creeps_enabled|false|cl,a||
|dota_hero_demo_towers_enabled|false|cl,a||
|dota_hero_god_mode|false|sv,cheat||
|dota_hero_grid_role_threshold_percent|30|cl||
|dota_hero_indicators_hide_distance|1000|cl,a,per_user||
|dota_hero_indicators_max_distance|4000|cl,a,per_user||
|dota_hero_indicators_max_radius|1|cl,a,per_user||
|dota_hero_indicators_min_radius|0.6|cl,a,per_user||
|dota_hero_muerta_dead_shot_debug|false|sv,cl,rep,cheat|Show debugging info for Muerta's dead_shot.|
|dota_hero_muerta_dead_shot_tolerance|0.1|sv|Tolerance for the Dead Shot ignoring the user's vector target and just shooting straight.|
|dota_hero_muerta_double_shot_debug|false|sv,cl,rep,cheat|Show debugging info for Muerta's double shot aiming.|
|dota_hero_muerta_double_shot_debug_offset|100|sv,cl,rep,cheat|Vertical offset for Muerta's double shot debug render.|
|dota_hero_muerta_double_shot_debug_sphere_size|20|sv,cl,rep,cheat|Sphere size for Muerta's double shot debug render.|
|dota_hero_multiple_kill_time|18|sv||
|dota_hero_overhead_names|0|cl,a,per_user||
|dota_hero_relic_debug_visuals|false|cl||
|dota_hero_selection_announcer_use_rr|true|cl|If enabled, use response rules for hero selection announcer lines|
|dota_hero_undying_max_zombies|64|sv|Maximum amount of zombies that can be spawned.|
|dota_heropicker_ad_select_time|10|sv,cheat||
|dota_heropicker_alldraft_banning_time|15|sv,cl,rep,cheat||
|dota_heropicker_alldraft_random_time|11|sv,cl,rep,cheat||
|dota_heropicker_alldraft_select_time|21|sv,cl,rep,cheat||
|dota_heropicker_ap_select_time|75|sv,cheat||
|dota_heropicker_ar_select_time|10|sv,cheat||
|dota_heropicker_ardm_select_time|10|sv,cheat||
|dota_heropicker_fh_select_time|60|sv,cheat||
|dota_heropicker_sd_select_time|60|sv,cheat||
|dota_heropicker_select_penalty_cost|2|sv,cheat||
|dota_heropicker_select_penalty_time|30|sv,cheat||
|dota_heropicker_tutorial_select_time|599|sv||
|dota_hide_cursor|false|cl|If set, mouse cursor is always hidden|
|dota_hide_fight_recap|cmd|cl|Hide the fight recap.|
|dota_hide_frontpage_video|false|cl,a|Don't load the frontpage streaming video.|
|dota_hide_spectator_player_names|false|cl||
|dota_hide_tips_on_loading_screens|false|cl,a,per_user||
|dota_hide_wearables|false|sv,cl,rep,cheat|If set, wearables (default body parts) will be hidden. This is for the item icon editor.|
|dota_highest_seen_item_id|28818530076|cl,a,per_user||
|dota_highlight_reel|false|cl||
|dota_highlight_reel_debug|false|cl,cheat||
|dota_highlight_reel_leadin_seconds|13|cl||
|dota_highlight_reel_leadout_seconds|5|cl||
|dota_highlight_reel_matchid|0|cl||
|dota_highlight_reel_playerid|-1|cl||
|dota_highlight_reel_running_time|180|cl||
|dota_hltv_camera_override_pos|0.0000000.000000|cl||
|dota_hltv_camera_use_override_pos|false|cl||
|dota_hold|cmd|cl||
|dota_hud_chat_fade_time|7|cl||
|dota_hud_chat_history_lines|15|cl|Number of history lines to save for in-game chat.|
|dota_hud_chat_wheel|true|cl||
|dota_hud_colorblind|0|cl,a,per_user|Which color mode to use for HUD elements (name is legacy)|
|dota_hud_combine_move_speed|true|cl|Combine base and bonus move speed numbers on the HUD|
|dota_hud_contextual_tips_disable|true|cl,a,per_user|Disable in-game contextual tips|
|dota_hud_custom_css_class|0|cl,cheat|Add a custom class to the root of the HUD for testing purposes.|
|dota_hud_custom_label_offset|16|cl||
|dota_hud_debug_name_all_entities|false|cl|If set, shows debug names for all entities.|
|dota_hud_disable_damage_numbers|false|cl,a,per_user|Hide the incoming and outgoing damage numbers.|
|dota_hud_extra_large_minimap|1|cl,a,per_user|Set minimap to extra large size|
|dota_hud_flip|false|cl,a,per_user|No longer used.  Use dota_minimap_position_option instead.|
|dota_hud_force_killcam|false|cl||
|dota_hud_force_query|false|cl,cheat|Left clicking a unit will force query selection to that unit.|
|dota_hud_force_rank_wagering|false|cl,cheat||
|dota_hud_force_wagering|false|cl,cheat||
|dota_hud_gameend|true|cl||
|dota_hud_gameend_dev|false|cl||
|dota_hud_gameend_dev_winning_team|2|cl||
|dota_hud_healthbar_disable_status_display|false|cl,a,per_user|Hide the overhead status text for hero status effects.|
|dota_hud_healthbar_hoveroutline_alpha|200|cl|Mouse hover outline brightness on healthbars|
|dota_hud_healthbars|3|cl|Show unit health bars, etc.|
|dota_hud_hide_mainhud|false|cl||
|dota_hud_hide_minimap|false|cl||
|dota_hud_hide_topbar|false|cl||
|dota_hud_ingame_predictions_hide|false|cl||
|dota_hud_ministun_duration|0.25|cl|Stuns lower than this will add UnitMiniStunned class to the HUD|
|dota_hud_netgraph|true|cl,a,per_user|Display net statistics on the hud|
|dota_hud_new_query_panel|false|cl,a|Enable new query panel|
|dota_hud_panorama_healthbars_hide|true|cl||
|dota_hud_popup_battlecup_fade_delay|3|cl||
|dota_hud_portrait_force_alive|false|cl||
|dota_hud_portrait_inset_bottom|0|cl||
|dota_hud_portrait_inset_left|2|cl||
|dota_hud_portrait_inset_right|2|cl||
|dota_hud_portrait_inset_top|3|cl||
|dota_hud_portrait_killer_inset_bottom|0|cl||
|dota_hud_portrait_killer_inset_left|2|cl||
|dota_hud_portrait_killer_inset_right|2|cl||
|dota_hud_portrait_killer_inset_top|3|cl||
|dota_hud_projection_debug|false|cl||
|dota_hud_queued_orders_enable|true|cl,a,per_user|If set, show shift-queued orders in the HUD.|
|dota_hud_queued_orders_max_orders|5|cl||
|dota_hud_queued_orders_timeout|60|cl||
|dota_hud_reduced_flash|false|cl,a|Reduce flashing in various gameplay effects.|
|dota_hud_show_crosshair_hero_tooltip|true|cl|Show/Hide the tooltip box that appears when you hover another hero.|
|dota_hud_show_minimal_shop|false|cl,a,per_user||
|dota_hud_show_overhead_events|true|cl|Show Crit, Gold, XP, etc. Overhead Event Messages|
|dota_hud_skins_enabled|true|cl|Enable HUD skins on the panorama HUD|
|dota_hud_unit_info|false|cl|Show health bars when the game or camera mode would ordinarily hide them.|
|dota_hud_victory_message_delay|2|cl|Delay before showing victory message in game end|
|dota_hud_victory_message_duration|4|cl|Duration victory message is shown in game end|
|dota_hud_voicechat_loud_value|0.6|cl||
|dota_hud_wager_spoof|cmd|sv|Spoof a wager for a specific player|
|dota_ice_grip|500|sv||
|dota_ice_grip_skates|2000|sv||
|dota_ice_slide|true|sv||
|dota_idle_acquire|true|sv,cheat||
|dota_idle_neutral_think_always|false|sv||
|dota_idle_rare_interval_max|25|sv,cheat||
|dota_idle_rare_interval_min|15|sv,cheat||
|dota_idle_rare_tower_scale|2|cl||
|dota_idle_time|300|sv|How long a player needs to be idle before he counts as disconnected.|
|dota_ignore_invites|false|cl,a,per_user|If set, guild invites and team invites will be automatically rejected|
|dota_ignore_nonfriend_invites|false|cl,a,per_user|If set, party and lobby invites from non-friends are ignored|
|dota_import_steam_inventory_layout|cmd|cl|Load the inventory layout from the Steam servers.|
|dota_inhibit_query_after_cast|0|cl,a||
|dota_international2023_rewards_level_animation_duration_max_change|200|cl||
|dota_international2023_rewards_level_animation_duration_max_seconds|5|cl||
|dota_international2023_rewards_level_animation_duration_min_change|1|cl||
|dota_international2023_rewards_level_animation_duration_min_seconds|0.5|cl||
|dota_inventory_combine_ground_items_radius|200|sv,cheat||
|dota_inventory_neutral_item_teleport_throw|150|sv,cheat||
|dota_invite_debug|cmd|cl|Prints local invite objects|
|dota_item_autocast|cmd|cl||
|dota_item_execute|cmd|cl||
|dota_item_free_buyback_end_time|30|sv,cl,rep,cheat||
|dota_item_free_disassemble_interval|10|sv,cl,rep,cheat||
|dota_item_fullprice_buyback_interval|10|sv,cl,rep,cheat||
|dota_item_quick_cast|cmd|cl||
|dota_item_suggestion_time|30|sv,cl,rep|Window for item suggestions.|
|dota_join_new_player_chat_channel|false|cl,a,per_user|If enabled, will automatically join the New Player chat channel for your language on startup.|
|dota_join_regional_chat_channel|false|cl,a,per_user|If enabled, will automatically join a chat channel for your region on startup.|
|dota_keybindings_cloud_disable|false|cl||
|dota_kill_all_bots|cmd|sv,cheat|Destroys all bots|
|dota_kill_buildings|cmd|sv,cheat|Kill buildings.|
|dota_kill_creeps|cmd|sv|Kill creeps.|
|dota_kill_streak_expire_time|6|cl,cheat||
|dota_kill_unit_by_name|cmd|sv,cheat|Kill a specific unit by unit name.|
|dota_killcam_history_time|20|sv,cl,rep||
|dota_lag_compensate_tracking_projectiles|true|cl|Advance tracking projectiles when their spawn is known to have been delayed by lag or packet loss.|
|dota_lag_compensation_test|0|sv,cheat||
|dota_lag_compensation_window|0|sv||
|dota_lan_lobby_port|27005|cl|Port to use for LAN lobby broadcast.  (Used for both sending and receiving.)|
|dota_lane_detection_distance|1200|sv||
|dota_lane_detection_duration|600|sv||
|dota_lane_detection_interval|5|sv||
|dota_lane_selection_hard_support|true|cl,a||
|dota_lane_selection_midlane|true|cl,a||
|dota_lane_selection_offlane|true|cl,a||
|dota_lane_selection_safelane|true|cl,a||
|dota_lane_selection_soft_support|true|cl,a||
|dota_last_acknowledged_plus_status|2|cl,a,per_user||
|dota_last_event_id|0|cl,a,per_user||
|dota_last_hit_multiple_kill_time|8|sv||
|dota_last_primary_event_id|48|cl,a||
|dota_launch_custom_game|cmd|cl,release,vconsole_fuzzy,vconsole_set_focus|Launch a custom game|
|dota_league_force_public|15438,15475,15689,15690,15691,15692,15693,15694,15728|cl|A comma separated list of league ids to force public usage|
|dota_league_info_batch_interval_s|1|cl||
|dota_league_postgame_time|3600|sv|How long to wait after in state disconnect for league games, so DVR delayed folks can keep watching.|
|dota_league_refresh_localization|cmd|cl|Refreshes the english localization file with all the latest league strings|
|dota_league_shared_dump|cmd|cl|Dumps the shared league data to the console|
|dota_learn_stats|cmd|cl|Show talents popup|
|dota_leaver_status|cmd|sv|List leaver status of players|
|dota_leftclick_cameragrip_new|false|cl,a,per_user|Enables mode which requires left-click to start camera motion in addition to the camera grip keybind.|
|dota_legacy_demo_combine|true|cl,rep||
|dota_lenient_idle_time|480|sv|How long a player needs to be idle before he counts as disconnected during the end stages of the game.|
|dota_letterbox_mode_fade_duration|5|cl,cheat||
|dota_lightning_fixed_angle|false|cl||
|dota_lightning_lerp_exponent|1|cl||
|dota_load_all_hero_sounds|cmd|cl,cheat|Loads all hero sound entries, for diagnostics|
|dota_load_demo_mode_scenario|cmd|sv|[input_file]|
|dota_loading_screen_battle_cup_dev|0|cl||
|dota_loadout_test_pet_offset|0.0000000.0000000.000000|cl,cheat||
|dota_lobby_browser_selected_gamemode|0|cl,a||
|dota_lobby_browser_selected_region|0|cl,a||
|dota_lobby_settings_advanced_visible|false|cl,a||
|dota_local_bot_match_difficulty|1|sv,cl,a,rep|Difficulty to play local bot matches against|
|dota_local_bot_match_script_index|0|cl,a||
|dota_local_map_strategy_time|false|sv,cheat||
|dota_mana_per_vertical_marker|250|cl|How much mana between each vertical line in the mana bars|
|dota_map_lines_max_allowance|30|sv,cheat||
|dota_map_lines_max_allowance_period_seconds|1|sv,cheat||
|dota_map_locations_debug|cmd|cl|Prints map location objects|
|dota_map_ping_multi_key_press|false|cl|If true, we can ping the map even if we have multiple keys pressed on the keyboard. Otherwise map pinging will only occur if alt is the only key pressed.|
|dota_match_game_modes|8388608|cl,a|Bit masks of game modes to search for in unranked matchmaking|
|dota_match_languages|4|cl,a|Bit masks of languages to search for in matchmaking|
|dota_match_signout_timeout|10|sv,cheat||
|dota_match_solo_fast_queue|true|cl,a,per_user|Search for solo queue competitive games for ranked roles.|
|dota_match_steam_group_account_id|0|cl|Steam Group to use when searching for matchmaking|
|dota_matchgroups_automatic|260|cl,a|Bit mask of match groups to search in for matchmaking if automatic detection is enabled|
|dota_matchgroups_new|388|cl,a|Bit masks of match groups to search in for matchmaking|
|dota_matchgroups_random_data|false|cl||
|dota_matchgroups_version|107|cl,a|Last known match groups version.  GC will bump this version to trigger confirmation of any manual user selections|
|dota_max_courier_purchase_limit|24|sv|Maximum allowed couriers per player (purchasing disallowed when reached)|
|dota_max_disconnected_time|300|sv|How long a player needs to be disconnected before he counts as a leaver and gets punished.|
|dota_max_hero_select_time|390|sv|How long a player has to choose their hero before being marked as AFK.|
|dota_max_pets|10|sv,cl,rep,cheat|Number of pets allowed in a single match.|
|dota_max_physical_items_drop_limit|6|sv|Maximum allowed physical items on ground per player for split items (tango/wards)|
|dota_max_physical_items_purchase_limit|24|sv|Maximum allowed physical items per player (purchasing disallowed when reached)|
|dota_max_videomode_matches|20|cl|Max number of video resolutions to show in UI.|
|dota_metadata_min_games_for_avg_stats|2|sv|Games required on a hero for average KDA to be valid and calibrated|
|dota_minimap_always_draw_hero_icons|true|cl,a,per_user|No longer used, please use dota_minimap_primary_option and dota_minimap_secondary_option instead.|
|dota_minimap_background_option|2|cl,a,per_user|Background options for minimap. 0 = None, 1 = Simple, 2 = Realistic|
|dota_minimap_create|cmd|cl,cheat|Does a bunch of work to create a minimap|
|dota_minimap_create_output_size|512|cl,cheat|Size of minimap texture generated with dota_minimap_create (512 default)|
|dota_minimap_creep_scale|1|cl||
|dota_minimap_disable_rightclick|false|cl,a|Disables right clicking on the minimap.|
|dota_minimap_draw_cocaster_camera|true|cl,a||
|dota_minimap_draw_fow|true|cl,cheat||
|dota_minimap_filter_amount|0.1|cl||
|dota_minimap_hero_name_shadowsize|8|cl,a||
|dota_minimap_hero_scalar|true|cl,a,per_user||
|dota_minimap_hero_scalar_distance|30|cl||
|dota_minimap_hero_scalar_minimum|625|cl||
|dota_minimap_hero_size|753.104|cl,a,per_user||
|dota_minimap_hero_spread|false|cl,a,per_user||
|dota_minimap_hero_spread_distance|2|cl||
|dota_minimap_hide_background|false|cl,a,per_user|No longer used, please use dota_minimap_background_option instead.|
|dota_minimap_misclick_time|0.2|cl,a,per_user|Minimum time after the mouse enters the minimap before we accept a move command. Used to prevent misclicks.|
|dota_minimap_options_migrated|true|cl,a,per_user|If false, will migrate from previous minimap options to new ones.  Should not be set manually because it can override your minimap settings.|
|dota_minimap_ping_chat_message_cooldown|1.5|cl,a||
|dota_minimap_ping_duration|3|cl,a||
|dota_minimap_ping_tag_duration|10|cl||
|dota_minimap_position_option|0|cl,a,per_user|Minimap on Left = 0, Minimap on Right = 1.|
|dota_minimap_power_rune_scale|1.5|cl||
|dota_minimap_primary_option|0|cl,a,per_user|Display options for primary minimap mode. 0 = Hero icon with arrow, 1 = Arrow with player colors, 2 = Arrow with team colors, 3 = Hero icon only|
|dota_minimap_rune_size|325|cl||
|dota_minimap_secondary_option|1|cl,a,per_user|Display options for secondary (alt) minimap mode. 0 = Hero icon with arrow, 1 = Arrow with player colors, 2 = Arrow with team colors, 3 = Hero icon only|
|dota_minimap_show_hero_icon|true|cl,a,per_user|If set, will show hero icons when you hold alt down. No longer used, please use dota_minimap_primary_option and dota_minimap_secondary_option instead.|
|dota_minimap_simple_background|false|cl,a,per_user|If true, the minimap will show a simplified background image.  No longer used, please use dota_minimap_background_option instead|
|dota_minimap_simple_colors|false|cl,a,per_user|No longer used, please use dota_minimap_primary_option and dota_minimap_secondary_option instead.|
|dota_minimap_tower_defend_distance|500|cl||
|dota_minimap_use_dynamic_mesh|true|cl||
|dota_modifier_debug|false|sv,cl,rep,cheat||
|dota_modifier_dump|cmd|sv,cheat|Dump all modifiers on all entities.|
|dota_modifier_test|cmd|sv,cheat|Creates a test modifier on unit|
|dota_mouse_spectator_window_lock|false|cl,a|If enabled, mouse will be locked to the window when in game and spectating in a mode that doesn't give camera control|
|dota_mouse_window_lock|true|cl,a|If enabled, mouse will be locked to the window when ingame|
|dota_muerta_easter_egg_hunt_chance|10|sv|% odds of a game having the egg hunt|
|dota_muerta_max_ofrendas|5|sv|How many ofrendas to get the guns.|
|dota_muerta_max_pledges|10|sv|How many pledges for the game to start.|
|dota_muerta_ofrenda_reveal_sequence_current_state|4|cl,a||
|dota_muerta_release_dont_show_ingame_event_description|true|cl,a,per_user||
|dota_muerta_release_event_enable_custom_versus_screen|true|cl,cheat||
|dota_muerta_release_event_fake_event_active|false|cl,cheat||
|dota_music_battle_debug|false|sv||
|dota_music_battle_distance|1000|sv||
|dota_music_battle_duration|2.5|sv||
|dota_music_battle_enable|true|sv||
|dota_music_battle_pre_time|2|sv||
|dota_music_battle_rest_time|10|sv||
|dota_music_battle_weight_trigger|40|sv||
|dota_music_enable_spectator_mode|true|sv,cl,rep||
|dota_music_gank_enemy_timer|2|sv||
|dota_music_spectator_battle_average|30|cl||
|dota_music_spectator_battle_min|15|cl||
|dota_music_spectator_debug_enable|false|cl||
|dota_mute_cobroadcasters|false|cl,a,user||
|dota_mute_other_coaches|false|cl||
|dota_neutral_color|255255255|cl||
|dota_neutral_color_cb|255255255|cl||
|dota_neutral_initial_spawn_delay|60|sv,rep,cheat|Time after 0|
|dota_neutral_spawn_fx_timing|2|sv,cheat|Time before neutral spawns to play effects.|
|dota_neutral_spawn_interval|60|sv,rep,cheat|Time between neutral creep camp respawns, starting at 1|
|dota_neutral_timer_alarm_pull_numbers_b|146|cl||
|dota_neutral_timer_alarm_pull_numbers_g|252|cl||
|dota_neutral_timer_alarm_pull_numbers_r|200|cl||
|dota_neutral_timer_alarm_pull_ring_b|66|cl||
|dota_neutral_timer_alarm_pull_ring_g|188|cl||
|dota_neutral_timer_alarm_pull_ring_r|98|cl||
|dota_neutral_timer_alarm_stack_numbers_b|158|cl||
|dota_neutral_timer_alarm_stack_numbers_g|232|cl||
|dota_neutral_timer_alarm_stack_numbers_r|253|cl||
|dota_neutral_timer_alarm_stack_ring_b|78|cl||
|dota_neutral_timer_alarm_stack_ring_g|191|cl||
|dota_neutral_timer_alarm_stack_ring_r|223|cl||
|dota_new_player|false|cl,a,per_user||
|dota_new_player_pool_matches_played|0|cl,a,per_user||
|dota_new_player_seen_learn_tab|true|cl,a,per_user||
|dota_no_minimap|false|cl||
|dota_npc_creep_pushback_enabled|true|sv||
|dota_npc_creep_pushback_height_scale|100|sv||
|dota_npc_creep_pushback_max_damage_amount|500|sv||
|dota_npc_creep_pushback_max_damage_force|1|sv||
|dota_npc_creep_pushback_max_random_force|1|sv||
|dota_npc_creep_pushback_max_time|0.6|sv||
|dota_npc_creep_pushback_min_damage_amount|100|sv||
|dota_npc_creep_pushback_min_damage_force|0|sv||
|dota_npc_creep_pushback_min_random_force|0.9|sv||
|dota_npc_creep_pushback_min_time|0.4|sv||
|dota_npc_creep_pushback_random_yaw|2|sv||
|dota_npc_creep_pushback_scale|200|sv||
|dota_npx_buff_bots_get_buff|false|sv||
|dota_npx_buff_kill_mult|1.5|sv||
|dota_npx_buff_max_deaths|4|sv||
|dota_npx_buff_max_value|80|sv||
|dota_number_of_samples_for_lane_prediction|8000|sv|Number of samples used to guess players lane selection|
|dota_ogre_magi_arcana_disable_streak_display|false|cl,a||
|dota_open_party_manual_accept_invites|false|cl,a,per_user|Set this to disable auto-accepting invites when the leader of an open party|
|dota_orders_update_bots_immediately|true|sv,cheat||
|dota_overhead_damage_threshold_percent|15|sv||
|dota_overhead_on_received_item|true|sv,cl,rep|Emit an overhead particle effect on receiving an item from an ally.|
|dota_overhead_on_received_item_use_model|true|cl||
|dota_overkill_threshold|0.33|sv,cheat||
|dota_override_dire_team_logo|0|cl||
|dota_override_dire_wins|0|cl||
|dota_override_radiant_team_logo|0|cl||
|dota_override_radiant_wins|0|cl||
|dota_override_series_type|0|cl||
|dota_pain_debug|false|cl||
|dota_pain_factor|3|cl||
|dota_pain_fade_rate|3|cl||
|dota_particle_camera_cull_distance|3200|cl,cheat||
|dota_particle_fow_debug|false|cl,cheat||
|dota_particle_off_camera_simrate|0.3333|cl,cheat||
|dota_particle_parallel_prerender|true|cl||
|dota_party_debug|cmd|cl|Prints local party objects|
|dota_path_report_time_ms|0|sv||
|dota_pause|cmd|cl|Send a game pause request.|
|dota_pause_behavior_score_use_majority|true|sv|Whether a majority of connected players must have low behavior score before low behavior score players can unpause|
|dota_pause_cooldown|2|sv,cheat||
|dota_pause_cooldown_time|300|sv|Number of seconds before a player is allowed to pause again|
|dota_pause_count|3|sv|Number of times a player is allowed to pause the game|
|dota_pause_countdown|3|sv,cheat||
|dota_pause_force_unpause_time|300|sv|Number of seconds after which the game will automatically unpause|
|dota_pause_game_pause_silently|false|sv,cl,rep,cheat||
|dota_pause_limit|180|sv,cheat||
|dota_pause_minigame_muted|false|cl,a||
|dota_pause_minimum_time_spent_paused|1|sv|Number of seconds the game *must* remain paused before an unpause (to prevent accidental pause/unpause on the same team).|
|dota_pause_minimum_time_spent_paused_bad_behavior|5|sv|Number of seconds the game *must* remain paused before someone with bad behavior can unpause it|
|dota_pause_same_team_resume_time|5|sv|Number of seconds resuming is restricted to the same team, after that either team can pause|
|dota_pause_same_team_resume_time_disconnected|30|sv|Number of seconds resuming is restricted to the same team if someone disconnected, after that either team can pause|
|dota_pending_replay_force_failure|false|cl||
|dota_pending_replay_num_retries|30|cl||
|dota_pending_replay_retry_seconds|300|cl||
|dota_periodic_resource_cache_duration_s|600|cl||
|dota_pet_aatest_threat|-1|sv,cheat||
|dota_pet_allow_infront|true|sv,cheat||
|dota_pet_creepdist_maxthreat|0.1|sv,cheat||
|dota_pet_creepdist_minthreat|0|sv,cheat||
|dota_pet_debug|false|sv,cheat||
|dota_pet_decay_rate|0.1|sv,cheat||
|dota_pet_disable_flee|false|sv,cheat||
|dota_pet_dist_cone|50|sv,cheat||
|dota_pet_dist_max|400|sv,cheat||
|dota_pet_dist_min|200|sv,cheat||
|dota_pet_dist_range|400|sv,cheat||
|dota_pet_dmg_threshold_panic|200|sv,cheat||
|dota_pet_emote_maxtime|30|sv,cheat||
|dota_pet_emote_mintime|10|sv,cheat||
|dota_pet_fleedir_persist_time|2|sv,cheat||
|dota_pet_herodist_maxthreat|0.5|sv,cheat||
|dota_pet_herodist_minthreat|0.1|sv,cheat||
|dota_pet_herodist_radius|1024|sv,cheat||
|dota_pet_itemcarry|120|sv,cheat||
|dota_pet_priorthreat_to_vanish|0.1|sv,cheat||
|dota_pet_reposition_maxtime|7|sv,cheat||
|dota_pet_reposition_mintime|4|sv,cheat||
|dota_pet_return_threshold|0.2|sv,cheat||
|dota_pet_return_threshold_time|10|sv,cheat||
|dota_pet_threat_rate|1|sv,cheat||
|dota_pet_threat_time|1|sv,cheat||
|dota_pick_hero|cmd|sv,cheat|Pick a hero for <player-id> <hero> [<random-seed>]|
|dota_ping|cmd|sv|Print out latency information|
|dota_ping_max_allowance|1|sv,cheat||
|dota_ping_max_allowance_period_seconds|0.25|sv,cheat||
|dota_ping_menu_delay|0.15|cl,a,per_user|Seconds to wait before showing the ping context menu.|
|dota_play_custom_server|0|cl||
|dota_play_custom_server_name|0|cl||
|dota_play_predict_hpq_state|true|cl||
|dota_player_add_summoned_to_selection|true|cl,a,per_user||
|dota_player_auto_repeat_right_mouse|true|cl,a,per_user||
|dota_player_cards_duplicate_display_ti10|1|cl,cheat||
|dota_player_cards_duplicate_display_ti9|1|cl,cheat||
|dota_player_channels_require_stop|false|cl,a,per_user||
|dota_player_draft_bots_pick_humans|false|sv||
|dota_player_draft_prefer_human_captains|false|sv||
|dota_player_draft_timebank_per_pick|5|sv||
|dota_player_draft_timebank_start|60|sv||
|dota_player_graphs_hide_last_time_dist|80|cl||
|dota_player_info_batch_interval_s|1|cl||
|dota_player_item_label_alt_delay|0.25|cl,a,per_user||
|dota_player_multipler_orders|false|cl,a,per_user|By setting this to 1, you will issue an order to all controllable units by holding down the CTRL key when you click|
|dota_player_profile_stats_cache_duration|120|cl||
|dota_player_selection_cycle_ignores_groups|false|cl,a,per_user||
|dota_player_simplified_controls|false|cl,a||
|dota_player_smart_multiunit_cast|true|cl,a||
|dota_player_status|cmd|sv|Gives a status update on all players.|
|dota_player_teleport_requires_halt|true|cl,a,per_user||
|dota_player_units_auto_attack_mode|1|cl,a,per_user||
|dota_playtest_recommended_heroes|0|sv,cl,rep,cheat|Required heroes in a playtest.|
|dota_playtest_required_heroes|0|sv,cl,rep,cheat|Required heroes in a playtest.|
|dota_plus_use_assistant|true|cl,a,per_user|When set, we default to Plus Assistant rather than the default guides|
|dota_poor_network_detection_debug_level|2|sv|Spew verbosity for poor network condition detection|
|dota_poor_network_detection_disconnects_total|3|sv|Total number of near-simultaneous disconnections required to declare poor network conditions|
|dota_poor_network_detection_loss_pct|0.5|sv|Packet loss threshold (0...1) for declaring a QoS stat interval to be 'bad'|
|dota_poor_network_detection_max_intervals_player|5|sv|Max number of bad intervals to count for a player|
|dota_poor_network_detection_min_intervals_player|3|sv|Player must have at least N bad intervals to count|
|dota_poor_network_detection_num_intervals_team|11|sv|Number of QoS stats intervals that must be 'bad' on each team.|
|dota_poor_network_detection_num_intervals_total|25|sv|Number of QoS stats intervals that must be 'bad' over the whole match.|
|dota_portal_trampoline_interval|-1|sv,rep,cheat||
|dota_portrait_animate|false|cl||
|dota_portrait_debug_item_def_index|0|cl,cheat|Enables icon modification shader for specific item def index.|
|dota_portrait_debug_no_modifier|false|cl,cheat||
|dota_portrait_hide_background|false|cl,cheat|Disable portrait backgrounds. Mostly useful for rendering portrait movies with alpha.|
|dota_portrait_hide_hero|false|cl,cheat||
|dota_portrait_reload|cmd|cl,cheat|Reload portrait data|
|dota_portrait_reload_file|cmd|cl|Reloads portrait data.|
|dota_portrait_test_pet|false|cl,cheat|Set to 1 to make the pet show up once.|
|dota_post_game|cmd|cl|Show post game lobby with a historical matchid|
|dota_post_game_debug_animate_progress|false|cl||
|dota_post_game_debug_heroes|-1|cl||
|dota_post_game_debug_mmr|false|cl||
|dota_post_game_fake_dire_team_id|0|cl||
|dota_post_game_fake_neutral_item_id|-1|cl||
|dota_post_game_fake_player_pic|0|cl||
|dota_post_game_fake_radiant_team_id|0|cl||
|dota_post_game_fake_replay_state|-1|cl||
|dota_post_game_force_animate_progress|false|cl||
|dota_post_game_level_graph_major_size|5|cl||
|dota_post_game_level_graph_minor_size|3|cl||
|dota_post_game_lobby|cmd|cl|Show post game lobby with current lobby|
|dota_post_game_player_graph_highlight|10|cl||
|dota_post_game_quick_commend|true|cl||
|dota_post_game_report_time|600|sv|Time after the signout completes that we can still report and commend players, given the lobby id|
|dota_post_game_reward_tracking_duration|10|cl||
|dota_postgame_finish_replay_time|15|sv|How long to wait after the end scoreboard panel to finish the replay|
|dota_prediction_result_dev|false|cl||
|dota_preview_hero|cmd|sv|Pick hero for previewing|
|dota_preview_hero_pitch_offset|0|cl,cheat||
|dota_preview_hero_roll_offset|0|cl,cheat||
|dota_preview_hero_x_offset|0|cl,cheat||
|dota_preview_hero_y_offset|0|cl,cheat||
|dota_preview_hero_yaw_offset|0|cl,cheat||
|dota_preview_hero_z_offset|0|cl,cheat||
|dota_preview_sticker|cmd|cl|<item_def_index> opens the preview page for a specified item def|
|dota_preview_teleport_channel_time|true|cl,a||
|dota_privatebeta_teamswap|0|sv||
|dota_pro_player_hide_sub_team_tags|true|cl||
|dota_profile_battle_report_stats_sort_priorities|0|cl,a||
|dota_profile_hero_stats_sort_priorities|-6-2-5-910-341-2-5-910-6-341|cl,a||
|dota_profile_teammate_stats_sort_priorities|-2-31|cl,a||
|dota_profile_teammate_stats_sort_priorities_old|0|cl,a||
|dota_projection_continue_offscreen_abilities|true|cl,a||
|dota_projection_embargo_enabled|true|cl,a||
|dota_projection_embargo_time|0.25|cl,a||
|dota_projection_enabled_ti6|true|sv,a||
|dota_projection_failsafe_timeout|10|cl||
|dota_projection_hero_pick_abilities|false|cl,a||
|dota_projection_hero_pick_max_time|3|cl,a||
|dota_projection_max_medium_layer|2|cl||
|dota_projection_max_top_layer|1|cl||
|dota_projection_multikill|true|cl||
|dota_projection_multikill_time|3|cl||
|dota_projection_note_away_team_highlight_base|123|cl||
|dota_projection_note_base_layer_day|100|cl||
|dota_projection_note_base_layer_day_flipped|101|cl||
|dota_projection_note_base_layer_dire_win|106|cl||
|dota_projection_note_base_layer_dire_win_flipped|107|cl||
|dota_projection_note_base_layer_night|102|cl||
|dota_projection_note_base_layer_night_flipped|103|cl||
|dota_projection_note_base_layer_pick|112|cl||
|dota_projection_note_base_layer_radiant_win|104|cl||
|dota_projection_note_base_layer_radiant_win_flipped|105|cl||
|dota_projection_note_first_blood_stage_left|110|cl||
|dota_projection_note_first_blood_stage_right|111|cl||
|dota_projection_note_first_blood_time|3|cl||
|dota_projection_note_game_paused|20|cl||
|dota_projection_note_godlike|84|cl||
|dota_projection_note_godlike_time|3|cl||
|dota_projection_note_home_team_highlight_base|118|cl||
|dota_projection_note_pick_highlight_stage_left|108|cl||
|dota_projection_note_pick_highlight_stage_right|109|cl||
|dota_projection_note_picks_transition|113|cl||
|dota_projection_note_picks_transition_flipped|114|cl||
|dota_projection_note_rampage|117|cl||
|dota_projection_note_strategy_time|21|cl||
|dota_projection_note_triple_kill|115|cl||
|dota_projection_note_ultra_kill|116|cl||
|dota_projection_picks_transition_time|3|cl||
|dota_projection_team_win_notes|true|cl,a||
|dota_projection_video_channel|0|cl||
|dota_puck_waning_rift_doubletap_distance|25|cl,cheat||
|dota_purchase_force_failure|0|cl||
|dota_purchase_quickbuy|cmd|cl|Attempt to purchase an item out of the quickbuy. Priority is left to right, skips over items not purchasable due to secret shop|
|dota_purchase_random_hero_relic_animation_final_delay_time|0.8|cl||
|dota_purchase_random_hero_relic_animation_max_delay_time|0.4|cl||
|dota_purchase_random_hero_relic_animation_min_delay_time|0.1|cl||
|dota_purchase_random_hero_relic_shards_tick_duration|0.5|cl||
|dota_purchase_random_hero_relic_slowdown_time|2|cl||
|dota_purchase_random_hero_relic_steady_time|1|cl||
|dota_purchase_stickybuy|cmd|cl|Attempt to purchase an item out of the sticky slot. Skips over items not purchasable due to secret shop|
|dota_qop_arcana_kill_credit_window|1.25|sv,cheat||
|dota_qop_arcana_melee_range|350|sv,cheat||
|dota_qop_arcana_speech_delay|2|sv,cheat||
|dota_qop_arcana_ui_delay|0|sv,cheat||
|dota_queen_of_pain_arcana_disable_display|false|cl,a||
|dota_query_inhibit_time|0.5|cl||
|dota_quest_challenge_selected|0|cl,a,per_user||
|dota_quest_selected|0|cl,a,per_user||
|dota_quickcast_onkeydown|false|cl,a,per_user|Enables mode where quickcast triggers the ability on key down instead of key up.|
|dota_quit_after_game|true|sv|Quit after a game is completed, do not hibernate|
|dota_quit_on_hibernate_after_lobby|true|sv|Always terminate after receiving a lobby, do not rehibernate|
|dota_radar|cmd|cl|Activate radar mode|
|dota_random_strength|0.35|sv||
|dota_range_display|0|cl|Displays a ring around the hero at the specified radius|
|dota_ranked_role_queue|true|cl,a||
|dota_rare_line_click_count|5|cl||
|dota_razor_arcana_disable_display|false|cl,a||
|dota_razor_arcana_melee_range|250|sv,cheat||
|dota_realtime_stat_keyframe_interval_s|10|sv|How often the server generates a keyframe of realtime stats|
|dota_realtime_stat_update_interval_s|1|sv|How often the server updates internal game state and checks whether it should update the GC with realtime stats|
|dota_recent_event|cmd|cl||
|dota_reconnect_idle_buffer_time|45|sv|How much extra time the player has after reconnecting before he gets marked as AFK.|
|dota_record_blend_scale|1|cl|Scales rate of crossfade between 1st and 3rd idle cycles.  A value of 10 means the 1st cycle is fully blended in by 1/10th of animation|
|dota_record_hero|cmd|sv|Pick hero for recording|
|dota_record_hero_next|cmd|sv|Switch to next hero|
|dota_record_hero_prev|cmd|sv|Switch to prev hero|
|dota_record_mode_webm|false|cl,cheat|Don't use this directly, use the dota_record_webm command.|
|dota_record_webm|cmd|cl|Record a hero for a transparent webm movie.|
|dota_recorder_auto_advance|true|cl,cheat|Automatically start recording the next hero when the current ends|
|dota_recorder_cycles|3|cl,cheat|How many cycles of the animation to record|
|dota_recorder_mode|1|cl,cheat|0 = avi of idle anim, 1 = tga sequence of idle anim, 2 = single tga from start of idle anim, 3 = PNG sequence of anim|
|dota_recorder_particle_settle_frames|10|cl,cheat|Number of frames to render the portrait for in order for particle systems to settle.|
|dota_recorder_use_card_portrait|false|cl,cheat|Use the hero selector card portrait setup|
|dota_recorder_use_default_items|true|sv,cheat|Use default items only when recording heroes.|
|dota_recorder_use_fullbody_portrait|0|cl,cheat|Use the fullbody portrait setup. If 2, use Morphling's position for all heroes.|
|dota_recorder_use_portrait_file|0|cl,cheat|Load camera setup from a specific portrait file|
|dota_recorder_use_portrait_position|true|cl,cheat|Use camera position/activity from the portrait setup|
|dota_redeem_item_code|cmd|cl|Redeem a legacy Dota item code.|
|dota_redirect_allies_voice_to_private_coaching_group|false|cl,a,per_user||
|dota_ref_winner_dire|cmd|sv|Causes the dire team to win|
|dota_ref_winner_radiant|cmd|sv|Causes the radiant team to win|
|dota_reload_podseats|cmd|cl|Reload ti_podseats.txt data|
|dota_reload_text_chat_macros|cmd|cl|Reload chat macros|
|dota_remove_ability|cmd|sv|Remove an ability from the player's hero. If no index is specified, remove all abilities except talents and stats.|
|dota_render_bottom_inset|0|cl||
|dota_render_top_inset|0|cl||
|dota_replay_manager_download_chunk_size|1048576|cl,a||
|dota_replay_manager_download_simultaneous_requests|3|cl,a||
|dota_replay_skip_exits_cinematic_mode|false|cl,a||
|dota_reset_camera_on_spawn|false|cl,a,per_user|If enabled, camera will reset to your hero when you respawn|
|dota_reset_muerta_ofrenda_state|cmd|cl||
|dota_respawn_roshan|cmd|sv,cheat|Respawn Roshan|
|dota_restrict_partner_type_chat|true|sv|Disallow chat between certain partner types|
|dota_road_to_ti_use_playtest_data|false|cl|Use SQL data from playtests to populate quests. Otherwise will use vdata from pro matches.|
|dota_roadtoti_test_pre_game|false|cl||
|dota_roshan_upgrade_rate|60|sv,cl,rep,cheat||
|dota_rp_hide_party_unless_open|false|cl,a,per_user|If set, party status will not be sent to friends via rich presence, unless the party is open|
|dota_run_rare_chance|0.1|sv,cheat||
|dota_salute_rate_limit_seconds|30|sv,cl,rep,cheat|The amount of seconds that you must wait before you can salute again.|
|dota_save_scenario|cmd|cl|[output_file] [-binary] [-nopretty] save scenario of the game currently being spectated|
|dota_saved_camera_pos_1|-2230.0000001630.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_10|0.0000000.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_2|2800.000000-2345.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_3|3870.000000-1930.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_4|-6220.0000003645.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_5|-530.000000-400.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_6|6145.000000-2840.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_7|0.0000000.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_8|0.0000000.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_9|0.0000000.0000000.000000|cl,a,per_user||
|dota_saved_camera_pos_doublepress_time|2|cl,a,per_user||
|dota_scale_unit|cmd|cl,cheat|Scales the unit to the target multiplier|
|dota_scenario_autosave|false|cl,a,release|Enable autosaves while spectating a match from lobby|
|dota_scenario_autosave_interval|10|cl,a,release|Interval in seconds between auto-saves|
|dota_scenario_autosave_remotely|false|cl,release|Allow autosaving while in HLTV/replay.  (Not saved in settings)|
|dota_scenario_enable|false|cl,a,release|Enable scenario ui in private lobbies|
|dota_scoreboard_force_visible|false|cl||
|dota_screen_shake|false|cl,a,per_user||
|dota_script_function_help|cmd|sv|Get help on registered script API functions and tables.|
|dota_scripted_replay|false|cl||
|dota_scripted_replay_camspeed|1|cl||
|dota_scripted_replay_file|0|cl||
|dota_season_toasts|true|cl||
|dota_select_all|cmd|cl||
|dota_select_all_others|cmd|cl||
|dota_select_ally|cmd|cl|selects an ally|
|dota_select_courier|cmd|cl|Select a courier, or snap camera to courier if already selected|
|dota_select_scout|cmd|cl|Select a scout, or snap camera to courier if already selected|
|dota_selected_broadcaster_player_id|0|cl||
|dota_selection_groups|true|cl,a,per_user|If set, certain units like spiderlings, eidolons and treants are considered groups for selection.|
|dota_selection_test|true|cl||
|dota_send_courier_killed|true|sv||
|dota_send_scout_killed|true|sv||
|dota_server_add_chat_mute_entries|false|sv||
|dota_server_allow_custom_games|0|sv|Where this server makes itself available to host custom games|
|dota_server_allow_mvp|true|sv||
|dota_server_lobby_debug|cmd|sv|Prints server lobby object|
|dota_server_long_frame_threshold_ms|100|sv|How long a frame must stall before we make a log message.|
|dota_server_projection_fow_check|true|sv||
|dota_server_projection_spectator_only|true|sv||
|dota_server_send_map_stats|true|sv||
|dota_server_watchdog_match_timeout_minutes|4320|sv||
|dota_server_watchdog_shutdown_after_signout_minutes|60|sv||
|dota_settings_healthbar_boss_creep_height_offset|-4|cl||
|dota_settings_healthbar_boss_creep_icon_size|24|cl||
|dota_settings_healthbar_boss_creep_width_offset|20|cl||
|dota_settings_quick_move|true|cl,a,per_user||
|dota_settings_quick_target_attack|true|cl,a,per_user||
|dota_settings_targeted_attack_move|true|cl,a,per_user||
|dota_settings_targeted_attack_move_radius|200|cl,cheat||
|dota_sf_force_ready_up_dialog|0|cl|1 to force dialog immediately, 2 to force ready dialog when we lose focus|
|dota_sf_game_end_delay|10|sv,cl,rep|Delay before the end game panel animation (XP + scoreboard) starts once a game is ended|
|dota_sf_victory_message_duration|3|cl|Duration victory message is shown in game end|
|dota_shards_button_shard_animation_duration_max_change|20000|cl||
|dota_shards_button_shard_animation_duration_max_seconds|5|cl||
|dota_shards_button_shard_animation_duration_min|0.5|cl||
|dota_shards_button_shard_animation_duration_min_change|500|cl||
|dota_shop_allow_hotkeys_on_shift|true|cl,a,per_user||
|dota_shop_common_items|item_ward_observeritem_ward_sentryitem_bottleitem_rapieritem_caster_rapieritem_aetherial_halo|cl,a,per_user|Common items list for the shop|
|dota_shop_force_hotkeys|false|cl,a,per_user||
|dota_shop_search_autofocus|false|cl,a,per_user|If enabled, focus will automatically be placed on the search box when opening the shop|
|dota_shop_speech_timer|30|cl,a||
|dota_show_cast_range|true|cl,a||
|dota_show_combatlog|cmd|cl||
|dota_show_data_driven_camera|cmd|cl,cheat|<camera_file>|
|dota_show_fight_recap|cmd|cl|Show the most recent fight recap.|
|dota_show_heightmap|false|sv,cheat||
|dota_show_hero_compare_page|cmd|cl|Shows a page with two heroes side by side.|
|dota_show_hero_finder|true|cl,a,per_user|If set, will show hero indicator when alt is held down|
|dota_show_itempickups|true|cl||
|dota_show_killgraph|cmd|cl||
|dota_show_nav_obstructions|false|sv,cheat||
|dota_show_nearby_tower_attack_range|true|cl,a||
|dota_show_object_obstructions|false|sv,cheat||
|dota_show_plus_assistant_violator|true|cl,a||
|dota_show_popular_items|false|cl,a,per_user||
|dota_show_quick_stats_damage_breakdown_enabled|true|cl,a||
|dota_show_sideshop|cmd|cl|Show Sideshop|
|dota_show_spectated_unit_orders|0|cl|Log unit orders from other players while spectating/watching replays. 1 = player perspective player, 2 = all players|
|dota_show_spectator_tournament_drops|true|cl,a|Set to 1 for spectators directly connected to the game server to be able to see tournament drop messages|
|dota_show_teleport_channel_time|true|cl,a||
|dota_show_test_item_def_page|cmd|cl|<item def> - show the page for testing a new item definition|
|dota_show_test_item_set_page|cmd|cl|<set name> - show the page for testing a new item set|
|dota_show_waiting_for_match_warning_timeout|600|cl,a||
|dota_showcase_admin_cache_duration_s|900|cl||
|dota_showcase_admin_moderation|cmd|cl||
|dota_showcase_admin_review_reports|cmd|cl||
|dota_silent_roshan|false|cl|Be quiet Rosh, the pros are trying to kill you|
|dota_smart_doubletap|true|cl,a,per_user||
|dota_soccer_air_time|2|sv,cl,rep,cheat||
|dota_soccer_drag_coefficient|-1|sv,cl,rep,cheat||
|dota_soccer_gesture_delay|0.25|sv,cl,rep,cheat||
|dota_soccer_goal_distance|125|sv,cl,rep,cheat||
|dota_soccer_goal_width_max|700|sv,cl,rep,cheat||
|dota_soccer_goal_width_min|300|sv,cl,rep,cheat||
|dota_soccer_height|150|sv,cl,rep,cheat||
|dota_soccer_magnus_coefficient|-1|sv,cl,rep,cheat||
|dota_soccer_magnus_falloff|-1|sv,cl,rep,cheat||
|dota_social_feed_cache_duration|300|cl||
|dota_sort_steam_inventory|cmd|cl|Sort the steam inventory layout.|
|dota_spatial_audio_mix|1|release|Mix value to blend spatial and non-spatial audio in Dota 2.|
|dota_spawn_creeps|cmd|sv|Force spawn of all lane creeps.|
|dota_spawn_creeps_mid|cmd|sv|Force spawn of all mid lane creeps.|
|dota_spawn_neutrals|cmd|sv|Force spawn of all neutrals.|
|dota_spawn_rune|cmd|sv|Spawns a rune|
|dota_spec_show_courierkills|true|cl||
|dota_spec_show_spellsteals|true|cl||
|dota_spec_talentchanges_show|true|cl||
|dota_special_attack_delay|0|sv,cheat||
|dota_spectate_pause_advance_frames|5|cl,a,per_user||
|dota_spectate_roshantimer_enable|true|cl||
|dota_spectator_auto_spectate_bot_games|false|cl|Automatically spectate the always-running bot game.|
|dota_spectator_auto_spectate_games|0|cl|Automatically spectate available games.  Set to a LeagueID to auto spectate games from that league.|
|dota_spectator_autospeed|0|cl|Toggle Directed mode auto speed control.|
|dota_spectator_autospeed_fast|2|cl||
|dota_spectator_autospeed_fastest|4|cl||
|dota_spectator_autospeed_slowmo|true|cl||
|dota_spectator_autospeed_slowmo_slow|0.4|cl||
|dota_spectator_autospeed_slowmo_slowest|0.2|cl||
|dota_spectator_broadcaster_mode|false|cl|Display hero selection in broadcaster mode.|
|dota_spectator_camera_min_time_to_change_chase_unit|5|cl||
|dota_spectator_debug|false|cl||
|dota_spectator_decreasereplayspeed|cmd|cl|Decrease replay speed|
|dota_spectator_directed_hero_timer|2|cl||
|dota_spectator_directed_maxdistance|820|cl||
|dota_spectator_directed_player_perspective|false|cl||
|dota_spectator_directed_spline_time|1|cl||
|dota_spectator_enable_edgepan_temporary_free_camera|true|cl,a|Enable spectator takeover camera when edge panning.|
|dota_spectator_fog_of_war|-1|cl|Set fog of war spectator mode. -1|
|dota_spectator_fowtoggle|cmd|cl||
|dota_spectator_graph|0|cl||
|dota_spectator_graph_networking_enabled|true|sv|0 to disable graph data networking for perf comparisons.|
|dota_spectator_graph_networking_override|false|sv|1 to enable graph data networking for all clients.|
|dota_spectator_graph_send_interval|1|sv|Seconds between each graph update and tranmission.|
|dota_spectator_hero_index|0|cl||
|dota_spectator_hudhide|cmd|cl||
|dota_spectator_hudshow|cmd|cl||
|dota_spectator_increasereplayspeed|cmd|cl|Increase replay speed|
|dota_spectator_inventory_snapshot_interval|30|sv|Seconds between inventory snapshots|
|dota_spectator_minimum_spawn_delay|1.5|cl|Hero spawning takes at least this long so that we can move the camera and play the particle effect|
|dota_spectator_mode|1|cl|Toggles the spectator mode|
|dota_spectator_options_autohide|true|cl,a||
|dota_spectator_options_enabled|true|cl||
|dota_spectator_pause_on_slow_frame_threshold|0|cl||
|dota_spectator_pausetoggle|cmd|cl|Toggle replay play/pause|
|dota_spectator_pin_open|true|cl,a,per_user||
|dota_spectator_revertcameraview|cmd|cl||
|dota_spectator_select_under_mouse|cmd|cl||
|dota_spectator_selection_mode|2|cl||
|dota_spectator_selectnexthero|cmd|cl||
|dota_spectator_selectprevioushero|cmd|cl||
|dota_spectator_shoulder_view|false|cl||
|dota_spectator_skip|cmd|cl|Skip replay by a number of seconds.|
|dota_spectator_skip_back_1|cmd|cl|Skip replay back by 1st increment|
|dota_spectator_skip_back_2|cmd|cl|Skip replay back by 2nd increment|
|dota_spectator_skip_fwd_1|cmd|cl|Skip replay forward by 1st increment|
|dota_spectator_skip_fwd_2|cmd|cl|Skip replay forward by 2nd increment|
|dota_spectator_spawn_duration|1.5|cl|Duration that the camera should stay on the spawned hero before resetting back to normal|
|dota_spectator_spawn_ui_delay|0.75|cl|Delay after the hero spawns before showing the name and playing the pick sound|
|dota_spectator_stats_panel|0|cl|Current spectator stats panel. 1 = scoreboard, 2 = gold+xp, 3 = items, 4 = graph, 5 = fantasy|
|dota_spectator_statstoggle|cmd|cl||
|dota_spectator_teamname_dire|0|cl|International 2012|
|dota_spectator_teamname_overrides|true|cl|International 2012|
|dota_spectator_teamname_radiant|0|cl|International 2012|
|dota_spectator_use_broadcaster_stats_panel|true|cl,a,per_user|Follow the broadcasters choice of stats display.|
|dota_spectator_watching_broadcaster|false|cl|Indicates if you are watching a broadcaster in player view, so that the handling of selection can be treated differently. Meaningless when not in player view spectator mode.|
|dota_spectre_arcana_disable_display|false|cl,a||
|dota_spectre_arcana_progress_delay|0.25|cl,a||
|dota_speech_emotes|true|sv|Set 0 to disable emotes.|
|dota_speech_hardcoded_respeak_delay|true|sv,cl,rep,cheat|Certain speech concepts will not be said more than once per (n) seconds. Set to 0 to disable.|
|dota_speech_level|0|cl,a|Mutes certain parts of the units speech|
|dota_speech_meepo_pitch|5|cl,cheat|Increase the pitch of every successive meepo voice by this many %|
|dota_speech_missinglane_call_interval|10|sv,cheat|Bots will call 'missing' on a lane no more than once per this many seconds.|
|dota_speech_missinglane_call_threshold|8|sv,cheat|Bots will call 'missing' on a lane if an opponent has been gone this many seconds.|
|dota_speech_mute_time|1|sv,cl,rep||
|dota_speech_proximity_interval|5|sv,cheat|Once per (n) seconds, one hero will poll for TLK_ALLY_NEARBY. Because there are ten heroes this means each hero will poll once per n*10 seconds. Set 0 to disable altogether.|
|dota_speech_proximity_radius|500|sv,cheat|Heroes nearer than this distance will poll for the TLK_ALLY_NEARBY concept.|
|dota_speech_proximity_radius_enemy|1000|sv,cheat|Enemy heroes nearer than this distance will poll for the TLK_ENEMY_NEARBY concept.|
|dota_speech_shop_dawdle_interval|15|sv|Play 'dawdling' line from shopkeeper after hero has been in shop this long.|
|dota_speech_shop_enter_interval|30|sv|At least this many seconds must pass between shopkeeper greeting someone to his shop.|
|dota_speech_shopkeeper|false|sv,cheat|Enable or disable shopkeepers' speech.|
|dota_speech_test|cmd|cl|Play an arbitrary speech VCD as if it were coming out of the local player.|
|dota_speech_test_cycle|cmd|cl||
|dota_spew_connected_players|false|sv|If enabled, server will spew connected player GC updates |
|dota_splash_ad_acknowledged_id|135|cl,a,per_user||
|dota_start_ai_game|false|sv,cl,rep||
|dota_start_party_ready_check|cmd|cl|Start a party ready check.|
|dota_state_disconnect|cmd|sv|Transition to disconnect state on a listen server|
|dota_steamcontroller_view_acceleration_exponent|1.4|cl,a||
|dota_steamcontroller_view_cardinal_bias|0.35|cl,a||
|dota_steamcontroller_view_cardinal_bias_diagonal|0.6|cl,a||
|dota_steamcontroller_view_distance_scale|1.1|cl,a||
|dota_steamcontroller_view_haptic_intensity|2|cl,a||
|dota_steamcontroller_view_mode|0|cl,a||
|dota_steamcontroller_view_sensitivity|-5|cl,a||
|dota_steamlearn_load_metadata|cmd|sv|[project_id] [published_version] Test loads the inference metadata for the specified project|
|dota_stencil_glows|true|cl|Enable stencil of glows.|
|dota_sticker_collection_tutorial_state|11|cl,a||
|dota_stickerbook_collision_offset|-0.0001|cl||
|dota_stickerbook_decal_depth|10|cl||
|dota_stickerbook_min_distance|440|cl||
|dota_stickerbook_raycast_length|1000|cl||
|dota_stickerbook_scale_max|3|cl||
|dota_stickerbook_scale_min|0.8|cl||
|dota_sticky_ping_wheel|false|cl||
|+dota_stop|cmd|cl||
|dota_store_available_items_duration|600|cl||
|dota_store_data_cache_duration|300|cl||
|dota_store_data_retry_delay|30|cl||
|dota_suggest_disable|false|sv||
|dota_suggest_disable_topn_requests|false|sv||
|dota_suggest_item_sequence_allow_threshold|0.02|sv||
|dota_suggest_item_sequence_dupe_multiplier|0.3|sv||
|dota_suggest_item_sequence_other_option_multiplier|0.25|sv||
|dota_suggest_item_sequence_threshold_full|15|sv||
|dota_suggest_item_sequence_threshold_start|6|sv||
|dota_suggest_item_threshold|0.01|sv||
|dota_suggest_lane_trilane_penalty|0.8|sv||
|dota_suggest_learn_disable|false|sv||
|dota_suggest_learn_disable_topn_requests|false|sv||
|dota_suggest_learn_error_backoff_s|5|sv||
|dota_suggest_learn_error_retry_s|2|sv||
|dota_suggest_learn_item_sequence_allow_threshold|0.01|sv||
|dota_suggest_learn_item_sequence_dupe_multiplier|0.3|sv||
|dota_suggest_learn_item_sequence_other_option_multiplier|0.7|sv||
|dota_suggest_learn_item_sequence_threshold_full|15|sv||
|dota_suggest_learn_item_sequence_threshold_start|6|sv||
|dota_suggest_learn_item_threshold|0.01|sv||
|dota_suggest_learn_lane_trilane_penalty|0.8|sv||
|dota_suggest_learn_pregame_items_reduction|0.9|sv||
|dota_suggest_learn_pregame_items_threshold|0.1|sv||
|dota_suggest_learn_spew_abilities|false|sv||
|dota_suggest_learn_spew_items|false|sv||
|dota_suggest_learn_spew_lanes|false|sv||
|dota_suggest_learn_spew_pregame_items|false|sv||
|dota_suggest_learn_spew_win_probability|false|sv||
|dota_suggest_learn_toobusy_backoff_s|10|sv||
|dota_suggest_learn_win_probability_interval|5|sv||
|dota_suggest_pregame_items_reduction|0.9|sv||
|dota_suggest_pregame_items_threshold|0.1|sv||
|dota_suggest_spew_abilities|false|sv||
|dota_suggest_spew_items|false|sv||
|dota_suggest_spew_lanes|false|sv||
|dota_suggest_spew_pregame_items|false|sv||
|dota_suggest_spew_win_probability|false|sv||
|dota_suggest_spew_win_probability_chat|false|sv||
|dota_suggest_win_probability_interval|5|sv||
|dota_suggestion_quick_buy_and_neutral_timeout|1|sv||
|dota_summoned_units_auto_attack_mode_2|2|cl,a,per_user||
|dota_suppress_invalid_orders|false|sv|Don't log invalid orders|
|dota_surrender_on_disconnect|true|sv|If enabled, a team will surrender if all players on that team disconnect|
|dota_sv_load_scenario_timeout|20|sv|Timeout to receive saved scenario from GC|
|dota_swap_mouse_spellcast|false|cl,a||
|dota_takeherophotos|cmd|cl|Take a single full body shot of each hero.|
|dota_talent_upgrade_attribute|cmd|cl|Level up talent attribute.|
|dota_talent_upgrade_stat_left|cmd|cl|Level up talent on the left.|
|dota_talent_upgrade_stat_right|cmd|cl|Level up talent on the right.|
|dota_taunt_base_cooldown|2|sv,cheat|The amount of time after a taunt is finished that you always have to wait before taunting again.|
|dota_taunt_second_cooldown|60|sv,cheat|If trying to spam taunts, then amount of time you have to wait until that will be allowed again.|
|dota_team_fandom_last_seen|1638320400|cl,a||
|dota_team_info_batch_interval_s|1|cl||
|dota_test_achievement_toast|cmd|cl|Create a toast for an achievement|
|dota_test_buyback|cmd|cl||
|dota_test_challenge|cmd|sv||
|dota_test_custom_game_save|cmd|sv,cheat|Test custom game saving, only available from dota_launch_custom_game|
|dota_test_disconnect_icon|cmd|cl|Test disconnect icon|
|dota_test_glyph|cmd|cl||
|dota_test_move_attack|false|sv||
|dota_test_neutral_item_ack|false|cl||
|dota_test_npc|cmd|sv|Creates a testing npc|
|dota_test_plus_challenge|cmd|sv||
|dota_test_teamshowcase|cmd|sv||
|dota_text_chat_mute_threshold_s|8|sv|Time threshold to flag a text chat as abusive if it's followed by a chat mute|
|dota_ti2023_quests_how_to_play_dismissed|true|cl,a,per_user||
|dota_ti_onstage_fake_team_0|0|cl||
|dota_ti_onstage_fake_team_1|0|cl||
|dota_ti_onstage_overlay|false|cl||
|dota_ti_onstage_pods|false|cl||
|dota_ti_onstage_pods_away_back|AWAYBACK|cl||
|dota_ti_onstage_pods_away_front|AWAYFRONT|cl||
|dota_ti_onstage_pods_buyback|true|cl||
|dota_ti_onstage_pods_buyback_available|true|cl||
|dota_ti_onstage_pods_buyback_duration|5|cl||
|dota_ti_onstage_pods_during_draft|true|cl||
|dota_ti_onstage_pods_force_video_0|0|cl||
|dota_ti_onstage_pods_force_video_1|0|cl||
|dota_ti_onstage_pods_home_back|HOMEBACK|cl||
|dota_ti_onstage_pods_home_front|HOMEFRONT|cl||
|dota_ti_onstage_pods_id|false|cl||
|dota_ti_onstage_pods_item_pickup|true|cl||
|dota_ti_onstage_pods_item_time|4|cl||
|dota_ti_onstage_pods_level_up_time|4|cl||
|dota_ti_onstage_pods_player_pics|true|cl||
|dota_ti_onstage_pods_rapier|true|cl||
|dota_ti_onstage_pods_reversed_seats|false|cl||
|dota_ti_onstage_pods_secret_info|false|cl||
|dota_ti_override_home_team|false|cl||
|dota_ti_podseats_data_file|scripts/tournaments/ti_podseats.txt|cl,a||
|dota_ti_winners_data_file|scripts/tournaments/ti_winners.txt|cl,a||
|dota_time_of_day_rate|0.001667|sv,cl,rep,cheat|Rate at which time of day changes relative to game seconds|
|dota_tod_slow_transition_speed|0.2|cl,cheat||
|dota_tod_transition_speed|1|cl,cheat||
|dota_toggle_assisted_camera_operator|cmd|cl|Toggle assisted camera operator mode. This is a hybrid of Directed mode with operator control.|
|dota_toggle_autoattack|cmd|cl||
|dota_toggle_autoattack_automatically_during_orders|false|cl,a,per_user||
|dota_toggle_broadcaster_cameraman|cmd|cl|toggle cameraman|
|dota_toggle_combatlog|cmd|cl||
|dota_toggle_free_camera|cmd|cl|Toggle free camera mode. Only available in DotaTV and replays.|
|dota_toggle_hero_movie_mode|cmd|cl|Show item details pages with minimal UI, for recording hero movies|
|dota_track_chat_mutes|false|sv,cheat|Track chat prior to a mute happening in sql?|
|dota_tree_try_to_make_solid|cmd|cl||
|dota_treerespawn|cmd|sv|Respawns all trees on the map.|
|dota_trivia_autoplay_sounds|true|cl,a|Determines whether or not to autoplay trivia sounds.|
|dota_trivia_chat_enabled2|false|cl,a||
|dota_trophies_cache_duration|300|cl||
|dota_turbo_courier_default_auto_deliver|false|cl,a,per_user||
|dota_turbo_matches_played|985|cl,a,per_user||
|dota_tutorial_actionpanel|true|sv,cl,rep||
|dota_tutorial_camera_location_dist|500|sv,rep||
|dota_tutorial_debug|true|sv,rep||
|dota_tutorial_disable_bot_situational_items|false|sv,cheat||
|dota_tutorial_force_bot_defend|false|sv,cheat||
|dota_tutorial_force_learn_ability|-1|sv,cl,rep||
|dota_tutorial_game|false|sv,cl,rep||
|dota_tutorial_heroselection|true|sv,cl,rep||
|dota_tutorial_move_location_dist|225|sv,rep||
|dota_tutorial_percent_bot_exp_decrease|0|sv,cheat||
|dota_tutorial_percent_damage_decrease|0|sv,cheat|Percentage decrease to apply on damage on the player character.|
|dota_tutorial_prevent_exp_gain|0|sv,cheat||
|dota_tutorial_prevent_start|false|sv,cheat||
|dota_tutorial_see_enemy|true|sv||
|dota_tutorial_show_tower_damage|false|sv,cheat||
|dota_tutorial_skip_pregame|false|sv,cheat||
|dota_tutorial_start|cmd|cl||
|dota_tutorial_start_lesson|0|sv,cl,rep||
|dota_tutorial_state_change_delay|2|sv,rep||
|dota_tutorial_stop_daynightcycle|false|sv,cheat||
|dota_tutorial_usemodifierforanim|true|sv||
|dota_twitch_top_streams_data_cache_duration|300|cl||
|dota_ui_armory_build_on_demand|true|cl||
|dota_ui_armory_is_category_view|true|cl,a,per_user||
|dota_ui_armory_item_duplicate|1|cl||
|dota_ui_popup_collectors_cache_available_voted_items|0|cl,a||
|dota_ui_popup_collectors_cache_available_voted_items_timestamp|0|cl,a||
|dota_underdraft_cache_duration|300|cl||
|dota_unit_alert_radius|500|sv,cheat||
|dota_unit_alert_range|1800|sv,cheat||
|dota_unit_anger_cooldown_override|-1|sv,cheat||
|dota_unit_anger_duration|2.3|sv,cheat||
|dota_unit_anger_radius_override|-1|sv,cheat||
|dota_unit_blocked_angle_threshold|0.1|sv,cheat||
|dota_unit_blocked_look_ahead_angle_threshold|0.7|sv,cheat||
|dota_unit_blocked_wait_time|0.15|sv,cheat||
|dota_unit_blocked_wait_time_long|0.4|sv,cheat||
|dota_unit_blocked_wait_time_mid|0.3|sv,cheat||
|dota_unit_cache_npc_searches|true|sv,cheat|Whether to reuse a unit's search cache every frame to avoid obstruction manager queries.|
|dota_unit_colour_threat_evaluation|false|cl||
|dota_unit_damage_event_window|2|sv,cheat|Window (in seconds) that we track damage events for future health value extrapolation.|
|dota_unit_debug_acquisition_range|false|sv,cheat|Shows the acquisition range for selected units (Green circle)|
|dota_unit_debug_attack|false|sv,cheat||
|dota_unit_debug_attack_range|false|sv,cheat|Shows the attack range for selected units (Red circle)|
|dota_unit_debug_vision_range|false|sv,cheat|Shows the vision range for selected units (Teal circle)|
|dota_unit_draw_paths|false|sv,cheat||
|dota_unit_health_bar_offset|-1|cl||
|dota_unit_hero_glows|false|cl||
|dota_unit_interact_flash_duration|0.2|cl,a||
|dota_unit_lean_angle|90|sv,cl,rep||
|dota_unit_lean_enable|true|sv,cl,rep||
|dota_unit_lean_rate|3|sv,cl,rep||
|+dota_unit_movetodirection|cmd|cl||
|dota_unit_relative_move_bounce|1|sv,cheat||
|dota_unit_short_path_search_debug|0|sv,cheat||
|dota_unit_show_bounding_radius|false|sv,cheat||
|dota_unit_show_collision_radius|false|sv,cheat||
|dota_unit_show_missing_selection_boxes|false|cl||
|dota_unit_show_selection_boxes|0|cl,cheat|Draws selection hitboxes. 0 = off, 1 = non-trees, 2 = trees, 3 = all entities.|
|dota_unit_sink_delay|4|cl||
|dota_unit_sink_speed|50|cl||
|dota_unit_use_player_color|true|cl||
|dota_unit_z_speed|200|cl||
|dota_unpause_countdown|3|sv,cheat||
|dota_unpause_mass_disconnect_cooldown|86400|sv,cheat||
|dota_update_connected_players_check_time|1|sv,cheat|How often the server should check if it needs to update the GC in seconds|
|dota_update_connected_players_send_time|2|sv,cheat|Minimum send interval|
|dota_update_connected_players_team_change|60|sv,cheat|max send interval|
|dota_update_connected_players_urgency_building_state|60|sv,cheat|max send interval|
|dota_update_connected_players_urgency_connect|30|sv,cheat|max send interval|
|dota_update_connected_players_urgency_disconnect_consequences|5|sv,cheat|max send interval|
|dota_update_connected_players_urgency_disconnect_noconsequences|30|sv,cheat|max send interval|
|dota_update_connected_players_urgency_gamestate_timeout|10|sv,cheat|max send interval|
|dota_update_connected_players_urgency_heartbeat|1800|sv,cheat|max send interval|
|dota_update_connected_players_urgency_herochanged|10|sv,cheat|max send interval|
|dota_update_connected_players_urgency_kills|60|sv,cheat|max send interval|
|dota_update_connected_players_urgency_mass_disconnect|3|sv,cheat|max send interval|
|dota_update_connected_players_urgency_spectator_count|60|sv,cheat|max send interval|
|dota_update_gc_connection_check_count|2|sv,cheat|How many tries we check if the GC is still connected before terminating due to no response|
|dota_update_gc_connection_check_time|1200|sv,cheat|How often the server should check the GC is still connected|
|dota_update_gc_server_info|600|sv,cheat|How often the server should check if it needs to update the GC in seconds|
|dota_upload_item_purchase_history_duration_threshold|1200|sv,cheat|match duration below which we will not upload item purchases|
|dota_upload_item_purchase_history_mmr_threshold|1000|sv,cheat|MMR below which we will not upload item purchases|
|dota_upload_match_state_history_duration_threshold|900|sv,cheat|match duration below which we will not upload item purchases|
|dota_upload_match_state_history_interval|30|sv,cheat|interval in seconds that we track game states|
|dota_upload_neutral_item_equip_history_duration_threshold|1200|sv,cheat|match duration below which we will not upload neutral item equips|
|dota_upload_neutral_item_equip_history_mmr_threshold|1000|sv,cheat|MMR below which we will not upload neutral item equips|
|dota_use_aghanims_postprocess_material|true|cl||
|dota_use_heightmap|true|cheat|Set to 0 to disable using heightmap when tracing vertical rays|
|dota_use_occluded_click_particle_effects|true|cl||
|dota_use_winter2022_postprocess_material|true|cl||
|dota_versus_scene_disable_heroes|false|cl||
|dota_video_config.DeviceID|7298|cl||
|dota_video_config.setting.aspectratiomode|1|cl||
|dota_video_config.setting.coop_fullscreen|0|cl||
|dota_video_config.setting.cpu_level|2|cl||
|dota_video_config.setting.defaultres|1920|cl||
|dota_video_config.setting.defaultresheight|1080|cl||
|dota_video_config.setting.dota_ambient_cloth|false|cl||
|dota_video_config.setting.dota_ambient_creatures|false|cl||
|dota_video_config.setting.dota_cheap_water|true|cl||
|dota_video_config.setting.dota_portrait_animate|false|cl||
|dota_video_config.setting.fullscreen|0|cl||
|dota_video_config.setting.fullscreen_min_on_focus_loss|0|cl||
|dota_video_config.setting.gpu_level|3|cl||
|dota_video_config.setting.gpu_mem_level|2|cl||
|dota_video_config.setting.high_dpi|0|cl||
|dota_video_config.setting.knowndevice|0|cl||
|dota_video_config.setting.mat_viewportscale|1|cl||
|dota_video_config.setting.mat_vsync|0|cl||
|dota_video_config.setting.mem_level|2|cl||
|dota_video_config.setting.nowindowborder|1|cl||
|dota_video_config.setting.recommendedheight|2160|cl||
|dota_video_config.setting.recommendedwidth|1900|cl||
|dota_video_config.setting.refreshrate_denominator|0|cl||
|dota_video_config.setting.refreshrate_numerator|0|cl||
|dota_video_config.setting.shaderquality|0|cl||
|dota_video_config.setting.useadvanced|1|cl||
|dota_video_config.setting.version|1|cl||
|dota_video_config.VendorID|4318|cl||
|dota_video_config.Version|0|cl||
|dota_view_store_item_details|cmd|cl|<itemdef>|
|dota_wagering_info_cache_duration|600|cl||
|dota_wait_for_players_battle_cup_present_time|10|sv|Time to stay after waiting for players succeeds when displaying battle cup winners|
|dota_wait_for_players_completed_delay|2|sv|How long to stay at the waiting-for-players UI after all players have loaded|
|dota_wait_for_players_failed_delay|3|sv|How long to stay at the waiting-for-players UI after all players have loaded|
|dota_wait_for_players_to_load|1|sv|If set, hero picking will be delayed until all players have loaded.|
|dota_wait_for_players_to_load_streaming_timeout|30|sv|Game will start after this time, even if all players haven't loaded yet|
|dota_wait_for_players_to_load_timeout|180|sv|Game will start after this time, even if all players haven't loaded yet|
|dota_watch_game_disable_client_validation|false|cl,cheat|Force disable client validation for spectating.|
|dota_watch_live_friend_score_boost|500|cl,cheat|Amount that friends in live games boost the game's sort score|
|dota_watch_live_league_id|0|cl,cheat|League ID for requested games|
|dota_watch_live_match_data_refresh_interval|1|cl||
|dota_watch_live_match_list_auto_refresh_interval|120|cl||
|dota_watch_live_match_list_refresh_interval|10|cl||
|dota_watch_live_request_period|30|cl,cheat|Amount that friends in live games boost the game's sort score|
|dota_watch_pause_at_the_end_of_all_replays|true|cl|Pause at the end of replays|
|dota_wearables_clientside|false|sv,cl,rep||
|dota_weekend_tourney_debug|cmd|cl|Prints local weekend tourney object(s), if any|
|dota_weekend_tourney_selected_division|2|cl,a|Default division ID to show for weekend leagues and such|
|dota_will_purchase_gold_remaining_max_remaining|1000|cl|On the 'I will purchase <item>' alert, the maximum amount of gold remaining when showing the remaining gold cost|
|dota_will_purchase_gold_remaining_min_cost|2000|cl|On the 'I will purchase <item>' alert, the minimum cost of an item to show the remaining gold cost|
|dota_windrunner_arcana_disable_hud_display|false|cl,a||
|dota_windrunner_focus_fire_fx_threshold|1|sv,cl,rep,cheat||
|dota_workshoptest|false|sv,cl,rep||
|dota_workshoptest_modelnew0|0|sv||
|dota_workshoptest_modelnew1|0|sv||
|dota_workshoptest_modelnew2|0|sv||
|dota_workshoptest_modelorg0|0|sv||
|dota_workshoptest_modelorg1|0|sv||
|dota_workshoptest_modelorg2|0|sv||
|dota_wraith_king_arcana_disable_display|false|cl,a||
|dota_wraith_king_arcana_hero_claim_bucket_1|0|cl,a,per_user||
|dota_wraith_king_arcana_hero_claim_bucket_2|0|cl,a,per_user||
|dota_wraith_king_arcana_hero_claim_bucket_3|0|cl,a,per_user||
|dota_wraith_king_arcana_hero_claim_bucket_4|0|cl,a,per_user||
|dota_wraith_king_arcana_hero_claim_bucket_5|0|cl,a,per_user||
|dota_wraith_king_arcana_map_show_all_alive|cmd|cl|Show every hero as alive|
|dota_wraith_king_arcana_progress_delay|1.5|cl,a||
|dotadev_bind|cmd|cl|For development|
|dotadev_binds_show|cmd|cl|For development|
|dotadev_unbind|cmd|cl|For development|
|dp_pull|0.3|sv,cheat||
|dp_radius|100|sv,cheat||
|dp_spirits|0|sv,cheat||
|drawcross|cmd|sv,cheat|Draws a cross at the given location  Arguments|
|drawline|cmd|sv,cheat|Draws line between two 3D Points.  Green if no collision  Red is collides with something  Arguments|
|dsp_automatic|0|demo||
|dsp_db_min|80|demo||
|dsp_db_mixdrop|0.5|demo||
|dsp_dist_max|1440|cheat,demo||
|dsp_dist_min|0|cheat,demo||
|dsp_mix_max|0.8|demo||
|dsp_mix_min|0.2|demo||
|dsp_off|false|cheat||
|dsp_vol_2ch|1|demo||
|dsp_vol_4ch|0.5|demo||
|dsp_vol_5ch|0.5|demo||
|dsp_volume|0.8|a,demo||
|dump_client_projectiles|cmd|cl|Spews a list of all client-side projectiles|
|dump_entity_report|cmd|cl,cheat|List all client-side entities in the scene|
|dump_globals|cmd|sv|Dump all global entities/states|
|dump_loc_token|cmd||List information on the given token|
|dump_localization_files|cmd||List all loaded localization files|
|dump_modifier_list|cmd|sv|Dumps all modifiers that exist in the game|
|dump_panorama_css_properties|cmd|release|Prints out all valid panorama CSS properties and their documentation|
|dump_panorama_events|cmd|release|print panorama event types and their documentation|
|dump_panorama_render_command_stats|cmd|||
|dump_secondary_scene_worlds|cmd|cl|Lists secondary scene worlds and ref counts|
|dump_visible_buffs|cmd|sv,cheat|Print out non-hidden buffs.|
|dumpparticlelist|cmd|release|Print out information on existing particle systems|
|dumpstringtable|cmd||Usage|
|echo|cmd|server_can_execute|Echo text to console.|
|echoln|cmd|release|Echo the command arguments on the console|
|econ_show_items_with_tag|cmd|cl|Lists the item definitions that have a specified tag.|
|enable_boneflex|true|cl,a||
|enable_priority_boost|cmd||Disable focus based priority boost|
|endmovie|cmd|norecord|Stop recording movie frames.|
|engine_allow_multiple_simulates_per_frame|false||When the client is catching up in low frame rate situations, should we run client simulate more than once a frame?|
|engine_allow_multiple_ticks_per_frame|false||When the client is catching up in low frame rate situations, should we run tick more than once a frame?|
|engine_client_tick_pad_enable|false|||
|engine_cpu_info_extended|12CPUs(6cores),Frequency|3.7GHz,Features|F/M/S 25/33/2 AuthenticAMD 'AMD Ryzen 5 5600X 6-Core Processor             ' SSE SSE2 SSE4.1 SSE4.2 AVX AVX2 MMX RDTSC RDTSCP CMOV FCMOV PCLMULQDQ (64-bit process) |
|engine_low_latency_sleep_after_client_tick|false|release|When r_low_latency is enabled, this moves the low latency sleep on tick frames to happen after client simulation.|
|engine_max_resource_system_update_time|5|||
|engine_no_focus_sleep|20|a||
|engine_no_focus_sleep_vconsole_suppress|true||When VConsole is in the foreground, don't trigger engine_no_focus_sleep behavior|
|engine_ostype|Windows11||OS type the engine is running on.|
|engine_platform_name_extended|pc64||Platform the engine is running on.|
|engine_render_only|false|||
|engine_rendersystem_init|-dx11||Rendersystem option requested (changing this does not change the rendersystem).|
|engine_rendersystem_shader_model|110||Rendersystem shader model in use (changing this does not change the shader model).|
|engine_rendersystem_used|-dx11(cfg-dx11)||Rendersystem option in use (changing this does not change the rendersystem).|
|engine_show_frame_multiple_ticks|false|||
|engine_show_frame_pacing|false|||
|engine_show_frame_ticks|false|||
|engine_sse42|true||turn on sse4.2 optimizations in the engine|
|engine_vr_max_ticks_to_simulate|3||Max number of ticks to simulate per frame, after which simulation will start to slow down compared to real time.|
|english|false|cl,user|If set to 1, running the english language set of assets.|
|ent_absbox|cmd|sv,cheat|Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.  Arguments|
|ent_actornames|cmd|sv,cheat|Displays the entity name for all entities that have ShouldDisplayInActorNames true in code|
|ent_actornames_font|Consolas|sv,cl,rep,cheat|ent_actornames font name|
|ent_actornames_fontsize|24|sv,cl,rep,cheat|ent_actornames font size|
|ent_animgraph_debug|cmd|sv,cheat|Displays debug draws about the given entity(ies) animgraph  Arguments|
|ent_animgraph_record|cmd|sv,cheat|Toggles recording of animgraph replay of the given entity(s)  Arguments|
|ent_animgraph_setvar|cmd|sv,cheat|Sets a variable on the animgraph of the given entity(s)  Arguments|
|ent_attachments|cmd|sv,cheat|Displays the attachment points on an entity.  Arguments|
|ent_autoaim|cmd|sv,cheat|Displays the entity's autoaim radius.  Arguments|
|ent_bbox|cmd|sv,cheat|Displays the movement bounding box for the given entity(ies) in orange.  Some entites will also display entity specific overlays.  Arguments|
|ent_call|cmd|sv,cheat|ent_call <funcname> <option|
|ent_cancelpendingentfires|cmd|sv|Cancels all ent_fire created outputs that are currently waiting for their delay to expire.|
|ent_characterize|cmd|sv|Spew PVS debug info for entity|
|ent_clear_debug_overlays|cmd|sv,cheat|Clears all debug overlays|
|ent_create|cmd|sv,cheat,vconsole_fuzzy|Creates an entity of the given designer or subclass name where the player is looking.|
|ent_debug_anim|cmd|cl|Use the specified entity for animation debugging.|
|ent_debug_draw_thinkers|false|sv,cl,rep||
|ent_find|cmd|sv,cheat|Find and list all entities with classnames or targetnames that contain the specified substrings. Format|
|ent_find_index|cmd|sv,cheat|Display data for entity matching specified index. Format|
|ent_fire|cmd|sv,cheat,vconsole_fuzzy|Usage|
|ent_fire_output|cmd|sv,cheat,vconsole_fuzzy|Usage|
|ent_grab|cmd|sv,cheat|grabs the object in front of the player. Options|
|ent_hierarchy|cmd|sv,cheat|Prints the entity hierarchy tree rooted at the specified ent(s)|
|ent_hitbox|cmd|sv,cheat|Displays the hitboxes for the given entity(ies).  Arguments|
|ent_info|cmd|sv,cheat|Usage|
|ent_joint_axis_size|4|sv||
|ent_joint_filter_substring|0|sv||
|ent_joint_names|true|sv||
|ent_joint_only_ik_joints|false|sv||
|ent_joint_use_bind_pose|false|sv||
|ent_joints|cmd|sv,cheat|Displays the joint names + axes an entity.  Arguments|
|ent_kill|cmd|sv,cheat|Kills the given entity(s)  Arguments|
|ent_messages|cmd|sv,cheat|Toggles input/output message display for the selected entity(ies).  The name of the entity will be displayed as well as any messages that it sends or receives.  Arguments|
|ent_messages_draw|false|sv,cl,rep,cheat|Visualizes all entity input/output activity.|
|ent_name|cmd|sv,cheat|Displays the entity name|
|ent_orient|cmd|sv,cheat|Orient the specified entity to match the player's angles. By default, only orients target entity's YAW. Use the 'allangles' option to orient on all axis.  Format|
|ent_picker|cmd|sv,cheat|Toggles 'picker' mode.  When picker is on, the bounding box, pivot and debugging text is displayed for whatever entity the player is looking at.  Arguments|
|ent_pivot|cmd|sv,cheat|Displays the pivot for the given entity(ies).  (y=up=green, z=forward=blue, x=left=red).   Arguments|
|ent_pivot_size|20|sv,a,cheat||
|ent_rbox|cmd|cl,cheat|Displays the total bounding box for the given entity(s) in green.  Some entites will also display entity specific overlays.  Arguments|
|ent_remove|cmd|sv,cheat|Removes the given entity(s)  Arguments|
|ent_remove_all|cmd|sv,cheat|Removes all entities of the specified type  Arguments|
|ent_revert_dormancy_change|false|cl||
|ent_rotate|cmd|sv,cheat|Rotates an entity by a specified # of degrees|
|ent_scale|cmd|sv,cheat|Scales entities. Arguments|
|ent_scenehierarchy|cmd|sv,cheat|Prints the entity scenenode hierarchy tree rooted at the specified ent(s)|
|ent_script_dump|cmd|sv,cheat|Dumps the names and values of this entity's script scope to the console  Arguments|
|ent_select|cmd|sv,cheat|Select or deselects the given entities(s) for later manipulation  Arguments|
|ent_setang|cmd|sv,cheat|Set entity angles|
|ent_setname|cmd|sv,cheat|Sets the targetname of the given entity(s)  Arguments|
|ent_setpos|cmd|sv,cheat|Move entity to position|
|ent_show_contexts|false|sv,cheat|Show entity contexts in ent_text display|
|ent_show_damage|cmd|sv,cheat|Sets damage display mode.  When on, you will see the amount of damage dealt over the target's head.|
|ent_show_response_criteria|cmd|sv,cheat|Print, to the console, an entity's current criteria set used to select responses.  Arguments|
|ent_showonlyattachment|0|sv,cheat||
|ent_skeleton|cmd|sv,cheat|Displays the skeleton for the given entity(ies).  Arguments|
|ent_skeleton_duration|0|sv,cl,rep,cheat|Duration of ent_skeleton display|
|ent_skeleton_only_ik_joints|false|sv||
|ent_steadystate_batchsize|20|sv|Max number of entities to transmit to player|
|ent_steadystate_delay|5|sv|Time in seconds without network state changes until an entity is considered for trickle updates|
|ent_steadystate_enable|true|sv||
|ent_steadystate_interval|0.1|sv|Rate at which entities can be trickled to players|
|ent_teleport|cmd|sv,cheat|Teleport the specified entity to where the player is looking.  Format|
|ent_test_interpolation|false|cl||
|ent_text|cmd|sv,cheat,vconsole_fuzzy|Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_text256|cmd|sv,cheat|Displays text debugging information about the given entity(ies) [within 256 units of the player] on top of the entity (See Overlay Text)  Arguments|
|ent_text_clear|cmd|sv,cheat|Hide text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_text_filter|cmd|sv,cheat|Set which ent_text filters you want|
|ent_text_flags_active|-1|sv,a,cheat||
|ent_text_no_name_really_i_mean_it|false|sv,cheat||
|ent_text_radius|cmd|sv,cheat|Displays text debugging information about the given entity(ies) [near the player] on top of the entity (See Overlay Text)  2 Arguments|
|ent_text_sticky_add|cmd|sv,cheat|Adds to list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_text_sticky_clear|cmd|sv,cheat|Clears the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_text_sticky_dump|cmd|sv,cheat|Spews the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_text_sticky_remove|cmd|sv,cheat|Removes from the list of names to display text debugging information about the given entity(ies) on top of the entity (See Overlay Text)  Arguments|
|ent_ungrab|cmd|sv,cheat|un-grabs all objects|
|ent_vcollide_wireframe|cmd|sv,cheat|Displays the interpolated vcollide wireframe pm am entity.  Arguments|
|ent_viewoffset|cmd|sv,cheat|Displays the eye position for the given entity(ies) in red.  Arguments|
|entity_log_load_unserialize|0|sv,cl,rep,cheat|Output unserialization of entities on map load. 0 - off, 1 - client/server, 2 - server, 3 - client|
|entity_lump_list|cmd||List all known entity lumps|
|entity_lump_spew|cmd||Dump the contents of an entity lump|
|entityreport|cmd|sv|Reports all extant entities. Optional 2nd arg is a substring of a classname that the list will be filtered by.|
|entitysummary|cmd|sv|Summarizes (by class) all extant entities. Optional 2nd arg is a substring of a classname that the list will be filtered by.|
|ents|cmd|sv|List server entities, sorted by spawn group|
|escape|cmd|release,clientcmd_can_execute|Escape key pressed.|
|event_points_activate_timeout|10|cl||
|exec|cmd|norecord,release|Execute a cfg file|
|exec_async|cmd|cheat,norecord|Execute a cfg file over time|
|execifexists|cmd|norecord,release|Execute a cfg file if file exists|
|execute_command_every_frame|0|cheat||
|explode|cmd|sv,cheat|Kills the player with explosive damage|
|explodevector|cmd|sv,cheat|Kills a player applying an explosive force. Usage|
|fade_debug_splitscreen_slot|-1|cl||
|fadein|cmd|sv,cheat|fadein {time r g b}|
|fadeout|cmd|sv,cheat|fadeout {time r g b}|
|fake_chat_members|0|cl|Number of users in chat channel.|
|fake_event_game_active|-1|cl||
|fake_event_game_countdown|-1|cl||
|fake_meta_xp|cmd|sv,cheat|Fake meta xp values|
|fantasy_craft_decode_title_awards|cmd|cl|<league_id> <award_number> Convert a title awards uint64 into which titles were awarded|
|fantasy_craft_populate_league_data|cmd|cl|<fantasy league id> adds teams to the fantasy crafting data for the given fantasy league id|
|fantasy_craft_reset_tablets|cmd|cl|<fantasy league id> Rerolls all attributes on all tablets for the account|
|fantasy_craft_reset_tutorial|cmd|cl|Resets the user back to the base tutorial state|
|fantasy_craft_set_roll_tokens|cmd|cl|<fantasy league id> <period id> <token_amount> Sets available roll tokens for the account|
|fantasy_craft_upgrade|cmd|cl|<fantasy league id> Upgrades the tablet to the appropriate level for the period|
|filesystem_buffer_size|0||Size of per file buffers. 0 for none|
|filesystem_fake_latency|0|||
|filesystem_max_stdio_read|16|||
|filesystem_native|true||Use native FS or STDIO|
|filesystem_report_buffered_io|false|||
|filesystem_unbuffered_io|true|||
|find|cmd|release|Find concommands with the specified string in their name/help text.|
|findflags|cmd|release|Find concommands by flags.|
|fire_extinguishes_under_water|false|sv,cl,rep||
|fire_use_modifier|false|sv,cl,rep||
|firetarget|cmd|sv,cheat||
|firstperson|cmd|cl,release,execute_per_tick|Switch to firstperson camera.|
|fog_color|-1.000000-1.000000-1.000000|cl,cheat||
|fog_colorskybox|-1.000000-1.000000-1.000000|cl,cheat||
|fog_enable|true|cl,cheat|Enable fog|
|fog_enableskybox|true|cl,cheat||
|fog_end|-1|cl,cheat||
|fog_endskybox|-1|cl,cheat||
|fog_hdrcolorscale|-1|cl,cheat||
|fog_hdrcolorscaleskybox|-1|cl,cheat||
|fog_maxdensity|-1|cl,cheat||
|fog_maxdensityskybox|-1|cl,cheat||
|fog_override|0|cl,cheat|Overrides the map's fog settings (-1 populates fog_ vars with map's values)|
|fog_override_color|cmd|cheat|Sets the fog color override|
|fog_override_enable|false|cheat|Use fog_override convars instead of world fog data|
|fog_override_end|3500|cheat||
|fog_override_exponent|2|cheat||
|fog_override_max_density|0.4|cheat||
|fog_override_start|1000|cheat||
|fog_start|-1|cl,cheat||
|fog_startskybox|-1|cl,cheat||
|fog_volume_debug|false|sv|If enabled, prints diagnostic information about the current fog volume|
|footstep_debug|false|sv,cl,rep||
|footstep_force_volume|-1|sv,cl,rep||
|force_leave_game_button|false|cl||
|fov_desired|75|cl,a,user|Sets the base field-of-view.|
|fow_client_nofiltering|0|cl,cheat|0 = normal, 1 = off|
|fow_client_show_stats|false|cl,cheat||
|fow_client_stats|cmd|cl,cheat|displays fog of war stats|
|fow_client_visibility|0|cl,cheat|0 = normal, 1 = off, 2 = never seen, 3 = seen|
|fow_debug_draw_height_override|0|sv,cl,rep||
|fow_degree_fade_in_rate1|4|sv,cl,rep,cheat|FoW area fade in rate #1 (greater than 1 is faster)|
|fow_degree_fade_in_rate2|4|sv,cl,rep,cheat|FoW area fade in rate #2 (greater than 1 is faster)|
|fow_degree_fade_in_rate_midpoint|0.5|sv,cl,rep,cheat|FoW area fade out rate midpoint (0.0 - 1.0)|
|fow_degree_fade_out_rate1|4|sv,cl,rep,cheat|FoW area fade out rate #1 (greater than 1 is faster)|
|fow_degree_fade_out_rate2|4|sv,cl,rep,cheat|FoW area fade out rate #2 (greater than 1 is faster)|
|fow_degree_fade_out_rate_midpoint|0.5|sv,cl,rep,cheat|FoW area fade out rate (0.0 - 1.0)|
|fow_entity_reveal_unseen_radius|0|sv,cl,rep|Radius in world space to reveal around all viewers from unseen state, regardless of visibility.|
|fow_entity_reveal_unseen_time|0.5|sv,cl,rep|Seconds over which an unseen area is revealed by radius checks, 0 is instant.|
|fow_server_show_stats|false|sv,cheat||
|fow_server_stats|cmd|sv,cheat|displays fog of war stats|
|fow_server_test_tempviewer|cmd|sv,cheat|test a temp viewer|
|fow_simd_unseen|true|sv,cl,rep||
|fow_tile_update_time|0|sv,cl,rep|FoW tile update time.|
|fp_trace|cmd||Toggle field path tracing to file |
|fps_max|0|a,release|Frame rate limiter.  0=no limit.  Does not apply to dedicated server.|
|fps_max_tools|120|a|Additional frame rate limit while in tools mode and a window other than the game window has focus. Note that fps_max still applies, this only allows the maximum frame rate for tools mode to be lower. 0=no tools specific limit.|
|fps_max_ui|0|a|Frame rate limiter while the game UI is displayed.  0=no limit.  Does not apply to dedicated server.|
|freecamera_accel|5|cl|Tweak this parameter to adjust Free Camera movement acceleration.|
|freecamera_fog_end|2500|cl|Fog end for Free Camera.|
|freecamera_fog_start|1800|cl|Fog start for Free Camera.|
|freecamera_max_speed|500|cl|Tweak this parameter to adjust Free Camera movement max speed.|
|freecamera_rotation_multiplier|10|cl|Tweak this parameter to adjust Free Camera mouse rotation.|
|freecamera_zfar|4500|cl|Fog start for Free Camera.|
|frontpage_overwrite_twitch_stream|0|cl||
|fs_async_threads|-1||Number of IO threads in async filesystem (-1 == auto)|
|fs_clear_open_duplicate_times|cmd||Clear the list of files that have been opened.|
|fs_dump_open_duplicate_times|cmd||Set fs_report_long_reads 1 before loading to use this. Prints a list of files that were opened more than once and ~how long was spent reading from them.|
|fs_fake_read_delay_ms|0||Add N ms of delay to every low-level read operation, to simulate a slow disk|
|fs_report_async_io|false|||
|fs_report_long_reads|0||0|
|fs_report_sync_opens|0|release|0|
|fs_spew_readfieldlist|cmd|cheat|index <threshold bytes>|
|fs_warning_mode|0||0|
|func_break_max_pieces|15|sv,a,rep||
|func_break_reduction_factor|0.5|sv||
|func_breakdmg_bullet|0.5|sv||
|func_breakdmg_club|1.5|sv||
|func_breakdmg_explosive|1.25|sv||
|g_debug_angularsensor|false|sv,cheat||
|g_debug_constraint_sounds|false|sv,cheat|Enable debug printing about constraint sounds.|
|g_debug_ragdoll_visualize|false|cl,cheat||
|g_ragdoll_fadespeed|600|cl||
|g_ragdoll_important_maxcount|2|sv,cl,rep||
|g_ragdoll_lvfadespeed|100|cl||
|g_ragdoll_maxcount|5|sv,cl,rep||
|gameevents_showeventlisteners|false||Show listening addition/removals|
|gameevents_showevents|0||Dump game events to console. (1 = Show Signaling, 2 = Show Posting also).|
|gameinstructor_dump_open_lessons|cmd|cl,cheat|Gives a list of all currently open lessons.|
|gameinstructor_dump_run_lesson_counts|cmd|cl,cheat|Gives a list of lessons that been completed or shown|
|gameinstructor_enable|true|cl,a,release|Display in game lessons that teach new players.|
|gameinstructor_find_errors|false|cl,cheat|Set to 1 and the game instructor will run EVERY scripted command to uncover errors.|
|gameinstructor_reload_lessons|cmd|cl|Shuts down all open lessons and reloads them from the script file.|
|gameinstructor_reset_counts|cmd|cl|Resets all display and success counts to zero.|
|gameinstructor_start_sound_cooldown|4|cl|Number of seconds forced between similar lesson start sounds.|
|gameinstructor_teach_lesson|cmd|cl|Force a specific lesson to be triggered|
|gameinstructor_verbose|0|cl,cheat|Set to 1 for standard debugging or 2 (in combo with gameinstructor_verbose_lesson) to show update actions.|
|gameinstructor_verbose_lesson|0|cl,cheat|Display more verbose information for lessons have this name.|
|gameui_hide|cmd|release|Hides the game UI|
|gc_secret_key|0|sv,prot|Secret key for authenticating with the GC |
|getpos|cmd|cl,cheat|dump position and angles to the console|
|getpos_exact|cmd|cl,cheat|dump origin and angles to the console|
|gfx_calculate_skin_diffusion_profile_dipole|cmd||Calculate a skin diffusion profile using scattering constants.|
|gfx_generate_6point_ball|cmd||Generates a reference 6-point lighting ball|
|gfx_generate_ao_cone_response|cmd||Generates a LUT for AO cone vs. sphere|
|gfx_generate_ao_sphere_response|cmd||Generates a LUT for AO proxy calculations|
|gfx_generate_arhosek_solar_radiance_image|cmd||Generate solar radiance image|
|gfx_generate_cone_cone_union_LUT|cmd||Generates a LUT for cone-cone union|
|gfx_generate_cone_cone_union_slice|cmd||Generates a LUT for cone-cone union|
|gfx_generate_ellipse_coneangle_LUT|cmd||Generates a LUT to give a cone angle from parameterized ellipse|
|gfx_generate_ggx_luts|cmd||Generate LUTs for modified GGX|
|gfx_generate_limb_darkening_datasets|cmd||EXR containing sky model limb darkening datasets|
|gfx_generate_poisson_disk|cmd||Generate a poisson disk of N samples using best-candidate sampling.|
|gfx_generate_preintegrated_brdf|cmd||Generate a pre-integrated BRDF LUT|
|gfx_generate_sh_ball|cmd||Generates a reference spherical harmonics lighting ball|
|gfx_generate_sh_skyboxes|cmd||Generates SH skyboxes|
|gfx_generate_sin_pulse_texture|cmd||Generate a sine pulse texture|
|gfx_generate_skin_diffuse_warp|cmd||Generate the diffuse warp lookup texture used for pre-integrated skin shading.|
|gfx_generate_skin_shadow_warp|cmd||Generate the shadow warp lookup texture used for pre-integrated skin shading.|
|gfx_generate_skin_shadow_warp_shadow_width|0.5||Remapped width of the shadow penumbra|
|gfx_generate_solar_datasets|cmd||EXR containing sky model solar datasets|
|gfx_generatemips_test|cmd||Test generate mips 32 bits|
|gfx_graph_cie_color_matching_approx_funcs|cmd||Graphs CIE1931 functions to make sure they look right|
|gfx_graph_lightmap_filter_kernels|cmd||Graphs the old broken filter kernel and candidates for new ones|
|gfx_hemioct_flat_normal_test|cmd||Determine which constant(s) to use to preserve flat normals under HemiOctohedron normal map encoding|
|gfx_load_skin_diffusion_profile|cmd||Load a measured diffusion profile.|
|gfx_load_skin_diffusion_profile_image|cmd||Load a custom skin diffusion profile.|
|gfx_load_skin_diffusion_profile_sum_of_gaussians|cmd||Load sum-of-gaussians skin diffusion profile.|
|gfx_make_gpu_scrambled_halton_code|cmd||Make some code for me|
|gfx_remove_obsolete_detail_modes|cmd||Remove F_DETAIL_TEXTURE 1 and 2|
|give|cmd|sv,vconsole_fuzzy|Give item to player.  Arguments|
|givecurrentammo|cmd|sv,cheat|Give a supply of ammo for current weapon.. |
|gl_clear|true|cl||
|gl_clear_gray|false|cl,cheat|Clear the back buffer to gray every frame.|
|gl_clear_randomcolor|false|cl,cheat|Clear the back buffer to random colors every frame. Helps spot open seams in geometry.|
|global_set|cmd|sv,cheat|global_set <globalname> <state>|
|glow_use_tolerance|0.85|cl,rep,cheat||
|god|cmd|sv,cheat|Toggle by default, or 0 to disable and 1 to enable. Player becomes invulnerable.|
|gpu_level|3|cl|GPU Level - Default|
|gpu_mem_level|2|cl|Memory Level - Default|
|grep|cmd|release|grep line for pattern, print out matching lines only|
|groups|cmd|sv|Show status of all spawn groups.|
|guidepanel_resetnag|cmd|cl|Resets the nag count on the guide panel|
|hammer_bevel_leave_edges|false|||
|hammer_dota_path_falloff|1|||
|hammer_dota_path_fixup|true|||
|hammer_dota_path_opacity|0|||
|hammer_dota_path_sharpness|0.5|||
|hammer_dota_path_use_material_settings|true|||
|hammer_dota_path_width|150|||
|hammer_draw_bounds|false|||
|hammer_draw_dirty_bounds|false|||
|hammer_draw_model_raytrace_data|false|||
|hammer_draw_model_skeleton|false|||
|hammer_draw_overlay_triangles_in_box|false|||
|hammer_face_debug_info|false|||
|hammer_gridnav_always_update|false|||
|hammer_gridnav_preview_radius|15|||
|hammer_gridnav_show_creature_blocking|true|||
|hammer_gridnav_show_hero_blocking|true|||
|hammer_gridnav_show_impassable|true|||
|hammer_gridnav_show_obstructions|true|||
|hammer_gridnav_show_ward_blocking|true|||
|hammer_isosurface_merge_tolerance|0|rep||
|hammer_isosurface_remove_interior|true|rep||
|hammer_isosurface_sample_offset|0.0001|rep||
|hammer_isosurface_subtract|false|||
|hammer_nav_attrib_color|60|||
|hammer_overlay_draw_projection_triangles|false|||
|hammer_parallel_terrain_update|false|||
|hammer_raytrace_debug_draw|0||Draw ray tracing environment debug visualization in Hammer|
|hammer_render_model_bounding_spheres|false|||
|hammer_show_light_truncation_error|false|||
|hammer_spawn_area_base_alpha|0|||
|hammer_spawn_area_outline_alpha|255|||
|hammer_tile_border_size|16|||
|hammer_vis_opacity|32|||
|hammer_world_trace_multisample|true|||
|hammer_world_trace_pack_rays|false|||
|help|cmd|release|Find help about a convar/concommand.|
|hero_grid_selected_config|1|ЧТОПИКАТЬ?|cl, a, per_user                  |
|hero_grid_selected_rank_tier|0|cl,a,per_user||
|+herochatwheel|cmd|cl|Opens hero chatwheel menu while held|
|hide_sf_shop|cmd|cl|hide shop|
|hideconsole|cmd|norecord,release|Hide the console.|
|host_force_frametime_to_equal_tick_interval|false|||
|host_force_max_frametime_to_tick_interval|false|||
|host_framerate|0|release|Set to lock per-frame time elapse.|
|host_timescale|1|rep,cheat|Prescale the clock by this amount.|
|host_timescale_dec|cmd|cheat|Decrement the timescale by one step|
|host_timescale_inc|cmd|cheat|Increment the timescale by one step|
|host_writeconfig|cmd|release|Saves out the user config values.|
|hostfile|host.txt|sv,release|The HOST file to load.|
|hostip|167772170|release|Host game server ip|
|hostname|yes,pls...|release|Hostname for server.|
|hostname_in_client_status|false|release|Show server hostname in client status.|
|hostport|27015|release|Host game server port|
|hud_fastswitch|0|cl,a||
|hud_max_minimap_distance|2600|cl||
|hud_reloadscheme|cmd|cl|Reloads hud layout and animation scripts.|
|hud_river_vial_ui_expanded|true|cl,a,per_user||
|hud_sticky_item_name|item_tpscroll|cl,a||
|hud_toggle_visibility|cmd|cl|Toggles the Hud on and off|
|hullivr_edge_merge_tan|0.02|rep|Should we try to straighten two faces connected to this edge? (tangent)|
|hullivr_faceisland_merge_disp|0|rep|Should we straighten face island if the displacement is this much? (inches)|
|hullivr_faceisland_merge_tan|0.04|rep|Should we try to straighten an island of faces deviating from their average normal (tangent)?|
|hullivr_version|3|rep||
|hurtme|cmd|sv,cheat|Hurts the player.  Arguments|
|ic|cmd|cl|interp entity count |
|ik_constraints_enabled|true|||
|ik_debug_all_chains_unique_color_per_chain|false|||
|ik_debug_ccd|0|||
|ik_debug_chain_to_filter_by|0|sv,cl,rep,cheat||
|ik_debug_constraints|-1|||
|ik_debug_dogleg3bone|0|||
|ik_debug_dogleg3bone_enabled|true|||
|ik_debug_fabrik_backwards_enabled|true|||
|ik_debug_fabrik_backwards_iteration_toggle|cmd|linked||
|ik_debug_fabrik_backwards_iterations|0|||
|ik_debug_fabrik_forwards_enabled|true|||
|ik_debug_fabrik_forwards_iteration_toggle|cmd|linked||
|ik_debug_fabrik_forwards_iterations|0|||
|ik_debug_perlin_solver|false|sv,cl,rep||
|ik_debug_planetilt|0|||
|ik_debug_planetilt_axis_length|20|||
|ik_debug_targets|false|||
|ik_enable|true|cheat|Enable IK.|
|ik_fabrik_align_chain|true|||
|ik_fabrik_backwards_enabled|true|||
|ik_fabrik_forwards_enabled|true|||
|ik_fabrik_override_num_iterations|-1|||
|ik_final_fixup_enable|true|||
|ik_hinge_debug_bone_index|-1|sv,cl,rep,cheat||
|ik_planetilt_enable|true|||
|ime_hkl_info|cmd|norecord|Spew IME HKL info.|
|ime_info|cmd|norecord|Spew IME info.|
|ime_supported_info|cmd|norecord|Spew IME Supported info.|
|imgui_set_selection|cmd|sv,cheat|Sets ImGui selection|
|imgui_set_status_text|cmd|sv,cheat|Sets ImGui header status text|
|import_wizard_spew|false|||
|impulse|cmd|cl,release|Triggers impulse command|
|in_button_double_press_window|0.22|sv,cl,rep|How short the time between presses needs to be for us to consider it a double-press|
|incrementvar|cmd|norecord,release|Increment specified convar value.|
|input_button_code_is_scan_code|false|a,per_user|Bind keys based on keyboard position instead of key name|
|input_filter_relative_analog_inputs|false|cl,a||
|input_forceuser|-1|cheat|Force user input to this split screen player.|
|inspectheroinworld|cmd|cl|Zoom into a selected hero in the world for a closer view.|
|instant_replay|true||Enable instant replay recording.|
|instant_replay_goto_tick|cmd||Goto a direct timestamp of the replay|
|instant_replay_goto_tick_relative|cmd||Goto a direct timestamp of the replay|
|instant_replay_history_limit|120||Maximum amount of minutes to save history (0 is unlimited).|
|instant_replay_history_limit_low|10||Maximum amount of minutes to save history on low memory (32 bit) systems (0 is unlimited).|
|instant_replay_live|cmd||If in replay, jumps back to live|
|instant_replay_pause|cmd||Pauses instant replay.|
|instant_replay_resume|cmd||Resumes instant replay.|
|instant_replay_skip|cmd||Number of seconds to skip back to instant replay from current position|
|instant_replay_skip_live|cmd||Number of seconds to skip back to instant replay from live|
|instant_replay_timescale|cmd||Sets instant replay speed.|
|instant_replay_togglepause|cmd||Toggles instant replay.|
|invnext|cmd|cl,server_can_execute||
|invnextselect|cmd|cl,server_can_execute||
|invprev|cmd|cl,server_can_execute||
|invprevselect|cmd|cl,server_can_execute||
|ip|0|release|Overrides IP for multihomed hosts|
|iv_debug|cmd|cl|Spew interpolated var info for entity.|
|iv_debugbone|0|release|Debug bone name for interpolation spew of CAnimationState.|
|iv_interp|cmd|cl|Spew interpolated var info for entity.|
|iv_off|cmd|cl|Turn off all interpolation variable spew.|
|iv_on|cmd|cl|Spew both interpolated var debug info and history for entity.|
|iv_parallel_latch|true|cl||
|iv_parallel_restore|false|cl||
|iv_wrapped_parallel_latch|true|cl||
|jointeam|cmd|sv|Join a team|
|joy_advanced|false|cl,a||
|joy_advaxisr|0|cl,a||
|joy_advaxisu|0|cl,a||
|joy_advaxisv|0|cl,a||
|joy_advaxisx|0|cl,a||
|joy_advaxisy|0|cl,a||
|joy_advaxisz|0|cl,a||
|joy_autosprint|0|cl|Automatically sprint when moving with an analog joystick|
|joy_axisbutton_threshold|0.3|a|Analog axis range before a button press is registered.|
|joy_axisr_deadzone|0.15|a,per_user||
|joy_axisr_relative|false|a,per_user||
|joy_axisu_deadzone|0.15|a,per_user||
|joy_axisu_relative|false|a,per_user||
|joy_axisv_deadzone|0.15|a,per_user||
|joy_axisv_relative|false|a,per_user||
|joy_axisx_deadzone|0.15|a,per_user||
|joy_axisx_relative|false|a,per_user||
|joy_axisy_deadzone|0.15|a,per_user||
|joy_axisy_relative|false|a,per_user||
|joy_axisz_deadzone|0.15|a,per_user||
|joy_axisz_relative|false|a,per_user||
|joy_circle_correct_mode|1|cl,a,per_user||
|joy_circle_correct_mode_vehicle|2|cl,a,per_user||
|joy_display_input|false|cl,a||
|joy_forward_sensitivity|1|cl,a,per_user||
|joy_movement_stick|false|cl,a,per_user|Which stick controls movement (0 is left stick)|
|joy_name|joystick|cl,a||
|joy_pitch_sensitivity|3|cl,a,per_user||
|joy_pitchsensitivity|1|cl,a,per_user||
|joy_response_look|0|cl,a,per_user||
|joy_response_move|9|cl,a,per_user||
|joy_response_move_vehicle|6|cl||
|joy_side_sensitivity|1|cl,a,per_user||
|joy_sidesensitivity|1|cl,a||
|joy_wingmanwarrior_centerhack|false|a|Wingman warrior centering hack.|
|joy_wingmanwarrior_turnhack|false|a|Wingman warrior hack related to turn axes.|
|joy_xcontroller_cfg_loaded|false|cl|If 0, the 360controller.cfg file will be executed on startup & option changes.|
|joy_yaw_sensitivity|3|cl,a,per_user||
|joy_yawsensitivity|-1|cl,a,per_user||
|joystick|false|cl,a|True if the joystick is enabled, false otherwise.|
|jpeg_quality|90||Set jpeg screenshot quality. [1..100]|
|jpeg_screenshot|cmd||Take a jpeg screenshot|
|key_findbinding|cmd|release|Find key bound to specified command string.|
|key_listboundkeys|cmd|release|List bound keys with bindings.|
|key_updatelayout|cmd||Updates game keyboard layout to current windows keyboard setting.|
|kick|cmd|norecord,release|Kick a player by name.|
|kickid|cmd|norecord,release|Kick a player by userid or uniqueid, with a message.|
|kickid_hltv|cmd|norecord,release|Kick a player by userid or uniqueid, with a message.|
|kill|cmd|sv,cheat|Kills the player with generic damage|
|killvector|cmd|sv,cheat|Kills a player applying force. Usage|
|labelled_debug_helper_arc_segments|20|sv,cl,rep,cheat||
|labelled_debug_helper_enabled|true|sv,cl,rep,cheat||
|labelled_debug_helper_scale|1|sv,cl,rep,cheat||
|labelled_debug_helper_show_position|false|sv,cl,rep,cheat||
|labelled_debug_helper_show_text|true|sv,cl,rep,cheat||
|labelled_debug_helper_skeleton_show_bone_names|true|sv,cl,rep,cheat||
|language_fake_unsupported_primary|false|cl||
|lastinv|cmd|cl,server_can_execute||
|lb_allow_time_sliced_shadow_map_rendering|true||Allow time-sliced shadow buffer rendering when enabled via gameinfo.gi|
|lb_barnlight_shadowmap_scale|1|release|Scale for computed barnlight shadowmap size|
|lb_bin_slices|8192|||
|lb_convert_to_barn_lights_falloff_match_point|0.15|||
|lb_csm_cascade_size_override|-1||Override width/height of individual cascades in the CSM|
|lb_csm_draw_alpha_tested|true|||
|lb_csm_draw_translucent|true|||
|lb_csm_override_staticgeo_cascades|false||Override Cascades that will render static objects with lb_csm_override_staticgeo_cascades_value|
|lb_csm_override_staticgeo_cascades_value|-1||If lb_csm_override_staticgeo_cascades, override value used to determine which cascades render static objects|
|lb_csm_receiver_plane_depth_bias|0.000001||Depth bias applied to shadow receiver|
|lb_cubemap_normalization_max|32|||
|lb_cubemap_normalization_roughness_begin|0.1|||
|lb_enable_binning|true|menubar_item|SceneSystem/LightBinner/Enable Binning|
|lb_enable_shadow_casting|true||Allow stationary/dynamic lights to cast shadows.|
|lb_shadow_map_culling|true|cheat||
|lb_shadow_texture_height_override|-1||Override height of shadow atlas texture|
|lb_shadow_texture_width_override|-1||Override width of shadow atlas texture|
|lb_show_light_fog_clipmap_cb_cost|false|cheat|Show cost of lights in fog clipmap constant buffer. yellow = 1 cost, red = 6 cost|
|lb_sun_csm_size_cull_threshold_texels|10||Size, in texels, where we will cull an object in the shadowmap|
|lb_tile_pixels|8|||
|lightquery_debug_direct_lighting|true|sv,cl,rep,cheat||
|lightquery_debug_indirect_lighting|true|sv,cl,rep,cheat||
|listdemo|cmd|release|List demo file contents.|
|listid|cmd||Lists banned users.|
|listip|cmd||List IP addresses on the ban list.|
|listRecentNPCSpeech|cmd|sv,norecord|Displays a list of the last 5 lines of speech from NPCs.|
|load|cmd|norecord,vconsole_fuzzy|Usage|
|loadout_test_activity_modifiers|0|cl,cheat||
|locator_topdown_style|false|cl|Topdown games set this to handle distance and offscreen location differently.|
|log|cmd||Enables logging to file, console, and udp < on | off >.|
|log_color|cmd|norecord,release|Set the color of a logging channel.|
|log_dumpchannels|cmd|norecord,release|Dumps information about all logging channels.|
|log_flags|cmd|norecord,release|Set the flags on a logging channel.|
|log_level|cmd|norecord,release|Set the spew level of a logging channel.|
|log_verbosity|cmd|norecord,release|Set the verbosity of a logging channel.|
|logic_npc_counter_debug|false|sv,rep,cheat||
|loop_dump|cmd||Print the listeners of the current loop mode|
|lrucache_flush|cmd||Flushes the specified cache|
|lrucache_reset_stats|cmd||Resets stats for the specified CUtlLRUCaches (or all if none specified)|
|lrucache_set_size|cmd||Sets the specified cache to the specified size|
|lrucache_stats|cmd||Spews information about all CUtlLRUCaches|
|lservercfgfile|listenserver.cfg|sv||
|lua_assert_on_error|false|||
|lua_report_memory|cmd|||
|lua_shipping_assert_on_error|false|||
|m_pitch|0.022|cl,a,per_user|Mouse pitch factor.|
|m_yaw|0.022|cl,a,per_user|Mouse yaw factor.|
|map|cmd|release,vconsole_fuzzy,vconsole_set_focus|map <mapname> |
|map_enable_background_maps|cmd|cl,cheat|Enables/disables portrait background maps|
|maps|cmd|release|Displays list of maps.|
|markup_group_ent_bbox|cmd|sv,cheat|markup_group_ent_bbox <markup_group name> -> toggle ent_bbox for all members of the named markup group|
|markup_group_ent_text|cmd|sv,cheat|markup_group_ent_text <markup_group name> -> toggle ent_text for all members of the named markup group|
|markup_group_spew|cmd|sv,cheat|Spew all current markup groups and their members|
|markup_volume_ref_cone_angle|135|sv||
|mat_clearshadercache|cmd||Clears the shader cache used for dynamic shader compile.|
|mat_colcorrection_disableentities|false|cl|Disable map color-correction entities|
|mat_colcorrection_editor|false|cl||
|mat_colcorrection_forceentitiesclientside|false|cl,cheat|Forces color correction entities to be updated on the client|
|mat_depthbias_shadowmap|0.0005|cl||
|mat_disable_dynamic_shader_compile|cmd||Reloads all shaders from vcs files until the next time mat_reloadshaders is called|
|mat_fullbright|0|cheat||
|mat_lpv_luxels|false|cheat||
|mat_luxels|false|cheat||
|mat_max_lighting_complexity|8|cheat||
|mat_overdraw|0|cheat|Visualize overdraw|
|mat_overdraw_color|0.0750000.1500000.300000|cheat||
|mat_print_dead_materials|cmd||Print loaded materials that have no valid layers due to not supporting any of the modes in gameinfo.gi.|
|mat_print_error_materials|cmd||Print loaded materials that are using the error shader or material.|
|mat_print_expensive_materials|cmd||Print materials sorted by cost heuristic|
|mat_print_material_info|cmd||Print info about a specific material|
|mat_print_materials|cmd||Print loaded materials. Takes an optional substring as an argument.|
|mat_print_materials_last_frame|cmd||Print materials used last frame|
|mat_print_materials_unused|cmd||Print materials that have never been used|
|mat_print_modes|cmd||Print supported rendering modes.|
|mat_print_shader_info|cmd||Print detailed info about a single shader. Takes a shader name (hero.vfx) as an argument.|
|mat_print_shader_quality|cmd||Print current shader quality setting|
|mat_print_shaders|cmd||Print loaded shaders. Takes a substring as an argument.|
|mat_print_textures|cmd||Print loaded textures in alphabetical order. Takes an optional substring as an argument.|
|mat_print_textures_size|cmd||Print loaded textures in ascending size order. Takes an optional substring as an argument.|
|mat_print_textures_size_in_memory|cmd||Print loaded textures in ascending size order as they are in memory. Takes an optional substring as an argument.|
|mat_reinitmaterials|cmd||Reinitializes all loaded materials, reloading their shaders.|
|mat_reloadmaterials|cmd||Reloads all materials. Takes an optional substring as an argument.|
|mat_reloadshaders|cmd||Reloads all shaders. Takes optional substrings of shader names to recompile as arguments.|
|mat_reset_material_costs|cmd||Reset material cost heuristic|
|mat_set_shader_quality|cmd||Force shader quality setting (valid values are 0 or 1)|
|mat_shading_complexity|false|cheat|Visualize shading complexity|
|mat_shading_complexity_color|1.0000000.5000000.250000|cheat||
|mat_shading_complexity_max_instruction_count|1024|cheat||
|mat_shading_complexity_max_register_count|128|cheat||
|mat_show_distance_field|0|cheat|0=Off, 1=Visualize trace from camera, 2=Visualize occlusion|
|mat_slopescaledepthbias_shadowmap|4|cl||
|mat_tonemap_bloom_scale|-1|cheat||
|mat_tonemap_bloom_start_value|-1|cheat||
|mat_tonemap_debug|0|||
|mat_tonemap_force_accelerate_exposure_down|-1|cheat||
|mat_tonemap_force_average_lum_min|-1|cheat|Override. Old default was 3.0|
|mat_tonemap_force_log_lum_max|-1|cheat||
|mat_tonemap_force_log_lum_min|-1|cheat||
|mat_tonemap_force_max|-1|cheat||
|mat_tonemap_force_min|-1|cheat||
|mat_tonemap_force_percent_bright_pixels|-1|cheat|Override. Old value was 1.0|
|mat_tonemap_force_percent_target|-1|cheat|Override. Old default was 45.|
|mat_tonemap_force_rate|-1|cheat||
|mat_tonemap_force_scale|0|cheat||
|mat_tonemap_force_use_alpha|-1|cheat||
|mat_tonemap_uncap_exposure|0|cheat||
|mat_viewportscale|1|cl|Scale down the main viewport (to reduce GPU impact on CPU profiling)|
|mat_wireframe|0|cheat|0=Off, 1=Surface Wireframe, 2=Transparent Wireframe|
|mem_compact|cmd||Compacts the heap|
|mem_dump|cmd||Dump memory stats to text file or <stdout>.|
|mem_level|2|cl|Memory Level - Default|
|mem_test|cmd|||
|mem_test_each_frame|false||Run heap check at end of every frame|
|mem_test_every_n_seconds|0||Run heap check at a specified interval|
|mem_test_quiet|false||Don't print stats when memtesting|
|memory|cmd||Print memory stats.|
|mesh_calculate_curvature_smooth_invert|false|sv,cl,rep,cheat||
|mesh_calculate_curvature_smooth_pass_count|3|sv,cl,rep,cheat||
|mesh_calculate_curvature_smooth_weight|1|sv,cl,rep,cheat||
|mic_listen_while_nonfocused|false|cl|Enables the ability for the mic to remain open if the window loses focus such as when a caster tabs out to adjust settings|
|midi_auto_connect_port|-1|cl,a|On init, attempt to connect to the device on this port|
|midi_connect_port|cmd|cl|Attempt to open a connection on the passed port ( or 0 if not specfied ). Will close existing connection|
|+midi_note|cmd|cl||
|midi_release|cmd|cl|Release any connected MIDI device|
|midi_reset_notes|cmd|cl|Send emergency Note OFF for all active notes on all channels|
|midi_status|cmd|cl|Dump info about connected MIDI devices|
|midi_test_off|cmd|cl|Send a test note OFF to the connected MIDI device|
|midi_test_on|cmd|cl|Send a test note ON to the connected MIDI device|
|minimap_create|cmd|cl,cheat|Does a bunch of work to create a minimap|
|mobile_fps_increase_during_charging|false|a|MOBILE_FPS_CONTROL|
|mobile_fps_increase_during_touch|true|a|MOBILE_FPS_CONTROL|
|mobile_fps_limit|30|a|MOBILE_FPS_CONTROL|
|model_combiner_dumpstats|cmd|cl|Dump the stats for the model combiner manager.|
|model_default_preview_sequence_name|0|sv,cl,a,rep||
|model_dump_convert_info|cmd|cl,linked|Print model load-time conversion info|
|motdfile|motd.txt|sv,release|The MOTD file to load.|
|mouse_disableinput|false||Set to disable mouse input|
|mouse_inverty|false|cl,a||
|movie_fixwave|cmd||Fixup corrupted .wav file if engine crashed during startmovie/endmovie, etc.|
|mp_allowspectators|true|sv,cl,rep|toggles whether the server allows spectator mode or not|
|mp_disable_autokick|cmd|sv,release|Prevents a userid from being auto-kicked|
|mp_fadetoblack|false|sv,cl,nf,rep|fade a player's screen to black when he dies|
|mp_forcecamera|0|sv,cl,rep,release|Restricts spectator modes for dead players|
|mp_forcerespawn|true|sv,nf||
|mp_friendlyfire|false|sv,cl,nf,rep,release|Allows team members to injure other members of their team|
|mp_restartgame|0|sv,release|If non-zero, game will restart in the specified number of seconds|
|mp_teamplay|false|sv,nf||
|mp_usehwmmodels|0|cl|Enable the use of the hw morph models. (-1 = never, 1 = always, 0 = based upon GPU)|
|mp_usehwmvcds|0|cl|Enable the use of the hw morph vcd(s). (-1 = never, 1 = always, 0 = based upon GPU)|
|multigpu_skip_semaphores|false|||
|multigpu_skip_transfers|false|||
|multiunit_frame_tall|44|cl||
|multiunit_frame_tall_three_col|66|cl||
|multiunit_frame_tall_two_col|104|cl||
|multiunit_frame_wide|64|cl||
|multiunit_frame_wide_three_col|84|cl||
|multiunit_frame_wide_two_col|130|cl||
|multiunit_page_next|cmd|cl|cycle to the next multiunit page|
|multiunit_page_prev|cmd|cl|cycle to the previous multiunit page|
|multiunit_x_gap|1|cl||
|multiunit_x_gap_three_col|3|cl||
|multiunit_x_gap_two_col|1|cl||
|multiunit_x_start|0|cl||
|multiunit_y_gap|15|cl||
|multiunit_y_gap_three_col|17|cl||
|multiunit_y_gap_two_col|15|cl||
|multiunit_y_start|0|cl||
|multvar|cmd|norecord,release|Multiply specified convar value.|
|name|yes,pls...|a,per_user||
|nav_add_to_selected_set|cmd|sv,cheat|Add current area to the selected set.|
|nav_add_to_selected_set_by_id|cmd|sv,cheat|Add specified area id to the selected set.|
|nav_avoid|cmd|sv,cheat|Toggles the 'avoid this area when possible' flag used by the AI system.|
|nav_avoid_obstacles|true|sv,cheat||
|nav_begin_deselecting|cmd|sv,cheat|Start continuously removing from the selected set.|
|nav_begin_drag_deselecting|cmd|sv,cheat|Start dragging a selection area.|
|nav_begin_drag_selecting|cmd|sv,cheat|Start dragging a selection area.|
|nav_begin_selecting|cmd|sv,cheat|Start continuously adding to the selected set.|
|nav_bfs_debug|0|sv,cheat||
|nav_clear_attribute|cmd|sv,cheat|Remove given nav attribute from all areas in the selected set.|
|nav_clear_attributes|cmd|sv,cheat|Clear all nav attributes of selected area.|
|nav_clear_selected_set|cmd|sv,cheat|Clear the selected set.|
|nav_corner_adjust_adjacent|18|cheat|radius used to raise/lower corners in nearby areas when raising/lowering corners.|
|nav_curve_alt|false|sv,cheat||
|nav_curve_iter|0|sv,cheat||
|nav_curve_lock|-1|sv,cheat||
|nav_curve_max_step|10|sv,cheat||
|nav_curve_set|-1|sv,cheat||
|nav_curve_step|0.02|sv,cheat||
|nav_debug_blocked|false|sv,cheat||
|nav_delete|cmd|sv,cheat|Deletes the currently highlighted Area.|
|nav_delete_all_hull|cmd|sv,cheat|Deletes all areas with given hull category.|
|nav_delete_marked|cmd|sv,cheat|Deletes the currently marked Area (if any).|
|nav_disconnect|cmd|sv,cheat|To disconnect two Areas, mark an Area, highlight a second Area, then invoke the disconnect command. This will remove all connections between the two Areas.|
|nav_drag_selection_volume_zmax_offset|32|sv,rep|The offset of the nav drag volume top from center|
|nav_drag_selection_volume_zmin_offset|32|sv,rep|The offset of the nav drag volume bottom from center|
|nav_draw_area_connections|false|sv,cheat||
|nav_draw_area_filled|true|sv,cheat||
|nav_draw_area_ground|false|sv,cheat||
|nav_draw_area_hull_support|false|sv,cheat||
|nav_draw_area_ids|false|sv,cheat||
|nav_draw_area_inset_margin|0|sv,cheat||
|nav_draw_area_should_be_destroyed|false|sv,cheat||
|nav_draw_area_split_by_nav_link_mgr|false|sv,cheat||
|nav_draw_area_split_by_obstacle_mgr|false|sv,cheat||
|nav_draw_area_ztest|false|sv,cheat||
|nav_draw_attribute_dynamic|0|sv,cheat|Draw all nav areas with this dynamic attribute|
|nav_draw_attribute_game|0|sv,cheat|Draw all nav areas with this game attribute|
|nav_draw_blocked|true|sv,cheat||
|nav_draw_blocked_connections|false|sv,cheat||
|nav_draw_connected_area_radius|1000|sv,cheat||
|nav_draw_externally_created|false|sv,cheat||
|nav_draw_jump_links|false|sv,cheat||
|nav_draw_limit|300|sv,cheat|The maximum number of areas to draw in edit mode|
|nav_draw_link_alignment|false|sv,cheat||
|nav_draw_links|false|sv,cheat||
|nav_draw_markup|true|sv,cheat||
|nav_draw_markup_offset|4|sv,cheat||
|nav_draw_mesh|true|sv,cheat||
|nav_draw_mesh_grid|false|sv,cheat|Draw the mesh's spatial grid structure around the edit cursor position.|
|nav_draw_mesh_offset|1|sv,cheat|Vertical offset for drawing the mesh (useful for flat planes where the mesh is often a fixed offset from the physical ground|
|nav_draw_space_cells|false|sv,cheat||
|nav_draw_space_fly|false|sv,cheat||
|nav_draw_space_neighbors|false|sv,cheat||
|nav_draw_space_portals|false|sv,cheat||
|nav_draw_space_radius|0|sv,cheat||
|nav_draw_space_swim|false|sv,cheat||
|nav_draw_vertex_normal|false|sv,cheat||
|nav_edit|0|sv,cheat|Set to one to interactively edit the Navigation Mesh. Set to zero to leave edit mode.|
|nav_edit_validate|false|sv,cheat|Validate navmesh structures.|
|nav_end_deselecting|cmd|sv,cheat|Stop continuously removing from the selected set.|
|nav_end_drag_deselecting|cmd|sv,cheat|Stop dragging a selection area.|
|nav_end_drag_selecting|cmd|sv,cheat|Stop dragging a selection area.|
|nav_end_selecting|cmd|sv,cheat|Stop continuously adding to the selected set.|
|nav_gen_add_jumps|true|cheat||
|nav_gen_agent_radius_buffer|0.5|cheat|Buffer to add to agent radius before passing to nav gen|
|nav_gen_clip_polys_to_clearance|true|cheat||
|nav_gen_clip_polys_to_clearance_debug|false|cheat||
|nav_gen_connect_allow_multiple|true|cheat||
|nav_gen_connect_angle|0.75|cheat||
|nav_gen_connect_angle_ignore_z|true|cheat||
|nav_gen_connect_dist_a|1|cheat||
|nav_gen_connect_dist_b|1.5|cheat||
|nav_gen_connect_dist_z_mult|0.5|cheat||
|nav_gen_connect_overlap|0.5|cheat||
|nav_gen_degen_limit|0.001|cheat||
|nav_gen_false|false|cheat|Always false|
|nav_gen_island_removal|false|cheat||
|nav_gen_island_removal_all_hulls|true|cheat||
|nav_gen_join_nonzup|true|cheat||
|nav_gen_jump_connection_min_overlap_ratio|1|cheat|Minimum edge overlap required for jump connection consideration as a percentage of agent radius|
|nav_gen_markup_split_expand|2|cheat||
|nav_gen_markup_split_tol_base|1|cheat||
|nav_gen_markup_split_tol_nonav|1|cheat||
|nav_gen_markup_split_tol_nonentity|8|cheat||
|nav_gen_match_ground|false|cheat||
|nav_gen_max_bottleneck_width|128|cheat||
|nav_gen_max_bottleneck_width_do_clip|true|cheat||
|nav_gen_max_edge_len|512|cheat||
|nav_gen_max_edge_len_do_clip|true|cheat||
|nav_gen_max_edge_len_split_tol|24|cheat||
|nav_gen_opt_to_quads|true|cheat||
|nav_gen_opt_to_quads_angle_limit|8|cheat||
|nav_gen_opt_to_quads_num_steps|6|cheat||
|nav_gen_opt_to_quads_planar_deviation_limit|4|cheat||
|nav_gen_opt_to_quads_se_limit_end|0.1|cheat||
|nav_gen_opt_to_quads_se_limit_start|0.000010|cheat||
|nav_gen_opt_to_quads_weld_limit_end|0.01|cheat||
|nav_gen_opt_to_quads_weld_limit_start|0|cheat||
|nav_gen_remove_vertical_polys|true|cheat||
|nav_gen_split_boundary_polys|false|cheat||
|nav_gen_split_multi_connection_polys|true|cheat||
|nav_gen_split_multi_connection_polys_tol|0.01|cheat||
|nav_gen_true|true|cheat|Always true|
|nav_gen_vertical_limit|88|cheat||
|nav_genrt_debug|false|sv,cheat||
|nav_genrt_no_splice|false|sv,cheat||
|nav_genrt_no_split|false|sv,cheat||
|nav_genrt_step|-1|sv,cheat||
|nav_lower_drag_volume_max|cmd|sv,cheat|Lower the top of the drag select volume.|
|nav_lower_drag_volume_min|cmd|sv,cheat|Lower the bottom of the drag select volume.|
|nav_mark|cmd|sv,cheat|Marks the Area or Ladder under the cursor for manipulation by subsequent editing commands.|
|nav_mark_attribute|cmd|sv,cheat|Set nav attribute for all areas in the selected set.|
|nav_max_vis_delta_list_length|64|cheat||
|nav_obstacle_genrt|false|sv,cheat||
|nav_obstacle_validate|false|sv,cheat||
|nav_obstruction_draw|0|sv,cheat||
|nav_obstruction_draw_change|false|sv,cheat||
|nav_obstruction_draw_dist|-1|sv,cheat||
|nav_obstruction_draw_island|0|sv,cheat||
|nav_obstruction_draw_island_hull|-1|sv,cheat||
|nav_obstruction_draw_movefail_blocking|false|sv,cheat||
|nav_path_debug|false|sv,cheat||
|nav_path_debug_compute_with_open_goal|0|sv,cheat||
|nav_path_draw_areas|false|sv,cheat||
|nav_path_draw_arrow|true|sv,cheat||
|nav_path_draw_climb_segments|true|sv,cheat||
|nav_path_draw_connected_areas|false|sv,cheat||
|nav_path_draw_ground_segments|true|sv,cheat||
|nav_path_draw_jump_segments|true|sv,cheat||
|nav_path_draw_ladder_segments|true|sv,cheat||
|nav_path_draw_link_segments|true|sv,cheat||
|nav_path_draw_tick|0|sv,cheat||
|nav_path_fixup_climb_up_segments|false|sv,cheat||
|nav_path_fixup_gap_segments|false|sv,cheat||
|nav_path_jump_process_debug|false|sv,cheat||
|nav_path_optimize|true|sv,cheat||
|nav_path_optimize_portals|true|sv,cheat||
|nav_path_optimizer_debug|0|sv,cheat||
|nav_path_record_draw_last_fail|false|sv,cheat||
|nav_path_record_enable|1|sv,cheat||
|nav_pathfind_debug_log|0|sv,cheat||
|nav_pathfind_draw|0|sv,cheat||
|nav_pathfind_draw_blocked|0|sv,cheat||
|nav_pathfind_draw_costs|false|sv,cheat||
|nav_pathfind_draw_fail|0|sv,cheat||
|nav_pathfind_draw_total_costs|false|sv,cheat||
|nav_pathfind_inadmissable_heuristic_factor|1|sv,cheat||
|nav_raise_drag_volume_max|cmd|sv,cheat|Raise the top of the drag select volume.|
|nav_raise_drag_volume_min|cmd|sv,cheat|Raise the bottom of the drag select volume.|
|nav_recall_selected_set|cmd|sv,cheat|Re-selects the stored selected set.|
|nav_remove_from_selected_set|cmd|sv,cheat|Remove current area from the selected set.|
|nav_search_lattice_initial_scale|3|sv||
|nav_search_lattice_progressive_scale|1.7|sv||
|nav_select_allow_blocked|true|sv,cheat|When selecting an area under nav_edit, allow area marked as blocked.|
|nav_select_area_id|-1|sv,cheat|Select nav area with matching ID.|
|nav_select_block_id|-1|sv,cheat|Select nav space block with matching ID.|
|nav_select_hull|0|sv,cheat|Restrict area selection to areas that can support a hull of the given category|
|nav_select_radius|cmd|sv,cheat|Adds all areas in a radius to the selection set|
|nav_select_with_attribute|cmd|sv,cheat|Selects areas with the given attribute.|
|nav_show_area_connections|true|sv,cheat|Show connections to selected area when true|
|nav_show_area_info_font|Consolas|sv,cheat||
|nav_show_area_info_font_size|-1|sv,cheat||
|nav_show_area_info_font_voffset|-11|sv,cheat||
|nav_show_area_verts|true|sv,cheat|Show area vertex positions|
|nav_show_area_water_info|true|sv,cheat||
|nav_show_potentially_visible|0|cheat|Show areas that are potentially visible from the current nav area|
|nav_smooth_calc_z|true|sv,cheat||
|nav_smooth_constrain_results|true|sv,cheat||
|nav_smooth_constrain_results_relax|0.006|sv,cheat||
|nav_smooth_constrain_spring|2|sv,cheat||
|nav_smooth_constrain_spring_relax|0.01|sv,cheat||
|nav_smooth_draw_accel|0|sv,cheat||
|nav_smooth_draw_boundary|0|sv,cheat||
|nav_smooth_draw_calc|false|sv,cheat||
|nav_smooth_draw_constraint_spline|false|sv,cheat||
|nav_smooth_draw_constraint_spring|0|sv,cheat||
|nav_smooth_draw_speed|0|sv,cheat||
|nav_smooth_enable|true|sv,cheat||
|nav_smooth_relax|true|sv,cheat||
|nav_smooth_relax_use_timesteps|false|sv,cheat||
|nav_smooth_separating_dist_override|0|sv,cheat||
|nav_smooth_spring_const_override|-1|sv,cheat||
|nav_smooth_spring_factor_deriv|0|sv,cheat||
|nav_smooth_spring_factor_dist|0|sv,cheat||
|nav_smooth_spring_factor_speed|0|sv,cheat||
|nav_smooth_spring_forward_dist_base|50|sv,cheat||
|nav_smooth_spring_forward_dist_time_limit|1|sv,cheat||
|nav_smooth_spring_max_dist|36|sv,cheat||
|nav_smooth_spring_tension_max_override|-1|sv,cheat||
|nav_smooth_spring_timestep_factor_accel|100|sv,cheat||
|nav_smooth_spring_timestep_factor_speed|100|sv,cheat||
|nav_smooth_spring_timestep_max|0.5|sv,cheat||
|nav_smooth_spring_timestep_min|0.1|sv,cheat||
|nav_smooth_spring_yaw_rotation_speed|50|sv,cheat||
|nav_smooth_spring_yaw_threshold|20|sv,cheat||
|nav_smooth_use_opt|true|sv,cheat||
|nav_space_select_dist|200|sv,cheat||
|nav_split|cmd|sv,cheat|To split an Area into two, align the split line using your cursor and invoke the split command.|
|nav_split_place_on_ground|false|cheat|If true, nav areas will be placed flush with the ground when split.|
|nav_split_show_line|false|sv,cheat|Show the free split line.|
|nav_store_selected_set|cmd|sv,cheat|Stores the current selected set for later retrieval.|
|nav_switch|cmd|sv|Switches to navmesh for the specified spawngroup|
|nav_test_bfs_lattice_dist_0|-1|sv,cheat||
|nav_test_bfs_lattice_dist_1|-1|sv,cheat||
|nav_test_bfs_lattice_dist_2|-1|sv,cheat||
|nav_test_bfs_lattice_hex|false|sv,cheat|Demonstrates searching hexagonal lattice over nav mesh.|
|nav_test_bfs_lattice_mark|2|sv,cheat||
|nav_test_bfs_lattice_simple|false|sv,cheat||
|nav_test_bfs_lattice_spacing_0|24|sv,cheat||
|nav_test_bfs_lattice_spacing_1|48|sv,cheat||
|nav_test_bfs_lattice_spacing_2|96|sv,cheat||
|nav_test_bfs_simple|false|sv,cheat||
|nav_test_boundary_zone_circle|0|sv,cheat||
|nav_test_boundary_zone_force|false|sv,cheat||
|nav_test_boundary_zone_grid_dim|90|sv,cheat||
|nav_test_boundary_zone_path|0|sv,cheat||
|nav_test_boundary_zone_rays|100|sv,cheat||
|nav_test_boundary_zone_rays_margin|-1|sv,cheat||
|nav_test_boundary_zone_rays_random|false|sv,cheat||
|nav_test_curve_opt|0|sv,cheat||
|nav_test_detour|false|sv,cheat||
|nav_test_find_nearest|false|sv,cheat|Calculate the nearest point on the navmesh to the trace point.  Uses selection from nav_select_hull.|
|nav_test_find_nearest_clear|false|sv,cheat|Calculate the nearest point on the navmesh to the trace point.  Uses selection from nav_select_hull.|
|nav_test_find_random_connected|false|sv,cheat|Demonstrates finding random points that are connected in the nav mesh to the start point.|
|nav_test_find_random_connected_dist_max|1000|sv,cheat||
|nav_test_find_random_connected_dist_min|100|sv,cheat||
|nav_test_find_z|0|sv,cheat||
|nav_test_force_npc_repath|false|sv,cheat||
|nav_test_genrt|false|sv,cheat||
|nav_test_genrt_place|false|sv,cheat||
|nav_test_level_hull|cmd|sv,cheat|Find entities that intrude into the nav mesh.  List those entities in console output, and display bounding boxes around them for a while.|
|nav_test_level_hull_move|cmd|sv,cheat||
|nav_test_multi_connection|false|sv,cheat||
|nav_test_npc_area|0|sv,cheat||
|nav_test_npc_collision|0|sv,cheat||
|nav_test_npc_collision_range|250|sv,cheat||
|nav_test_npc_collision_show_geometry|false|sv,cheat||
|nav_test_path|false|sv,cheat|Calculate and draw a path from player/camera position to the test position.|
|nav_test_path_expansion_search|0|sv,cheat|Extend nav_test_path by doing an expansion search on that path.  Convar value defines dist.|
|nav_test_path_lock_goal|false|sv,cheat|Lock the pathfinding goal to the current intersection point.|
|nav_test_path_lock_start|false|sv,cheat|Lock the pathfinding start to the current intersection point.|
|nav_test_path_move|false|sv,cheat||
|nav_test_path_opt|true|sv,cheat|Enable path optimization for nav_edit_path paths.|
|nav_test_path_opt_transitions|false|sv,cheat||
|nav_test_path_return|false|sv,cheat|Calculate a return path from cursor position to the path calculated by nav_test_path.|
|nav_test_path_space|0|sv,cheat|Should nav_test_path test 3d navigation?  1 = space to space, 2 = multi-modal space/ground|
|nav_test_path_space_fly|true|sv,cheat|Test flight paths|
|nav_test_path_space_swim|true|sv,cheat|Test swim paths|
|nav_test_pos_name|0|sv||
|nav_test_pos_place|-1|sv||
|nav_test_ray_space|false|sv,cheat||
|nav_test_rays|false|sv,cheat||
|nav_test_smooth|false|sv,cheat||
|nav_test_smooth_extern_push|0|sv,cheat||
|nav_test_smooth_in_speed|120|sv,cheat||
|nav_test_smooth_in_yaw|0|sv,cheat||
|nav_test_smooth_path_speed|-1|sv,cheat||
|nav_test_smooth_separating_dist|-1|sv,cheat||
|nav_test_smooth_spring_const|-1|sv,cheat||
|nav_test_smooth_spring_tension_max|-1|sv,cheat||
|nav_test_spline|0|sv,cheat||
|nav_test_split_obstacle|0|sv,cheat||
|nav_test_split_obstacle_dirty|false|sv,cheat||
|nav_test_split_obstacle_leave|false|sv,cheat||
|nav_test_split_obstacle_size|30|sv,cheat||
|nav_test_split_obstacle_update_pos|true|sv,cheat||
|nav_toggle_deselecting|cmd|sv,cheat|Start or stop continuously removing from the selected set.|
|nav_toggle_in_selected_set|cmd|sv,cheat|Remove current area from the selected set.|
|nav_toggle_selected_set|cmd|sv,cheat|Toggles all areas into/out of the selected set.|
|nav_toggle_selecting|cmd|sv,cheat|Start or stop continuously adding to the selected set.|
|nav_unmark|cmd|sv,cheat|Clears the marked Area or Ladder.|
|nav_validate|0|cheat|Level of validation for nav system.  Higher will be slower.|
|nav_volume_debug|0|sv,cheat|Draw or print debug information about nav volume queries.|
|navnetsolve_draw_tri|-1|sv||
|navspace_create_water_smooth_connections|true|sv,cheat||
|navspace_create_water_transition_connections|true|sv,cheat||
|navspace_debug_pathfind|-1|sv,cheat||
|navspace_debug_stringpull|1|sv,cheat||
|navspace_debug_trace|0|sv,cheat||
|navspace_debug_transition_calc|0|sv,cheat||
|navspace_draw_water_changes|0|sv,cheat|Draw changes in water volumes|
|navspace_path_use_water_level_locator|true|sv,cheat||
|nb_command|cmd|sv,cheat|Sends a command string to all bots|
|nb_debug|cmd|sv,cheat|Debug NextBots.  Categories are|
|nb_debug_filter|cmd|sv,cheat|Add items to the NextBot debug filter. Items can be entindexes or part of the identifier of one or more bots.|
|nb_debug_history|false|sv,release|If true, each bot keeps a history of debug output in memory|
|nb_delete_all|cmd|sv,cheat|Delete all non-player NextBot entities.  Equivalent to script 'NextBotManager.DeleteAll(...)'|
|nb_force_look_at|cmd|sv,cheat|Force selected bot to look at the local player's position|
|nb_freeze|false|sv,rep,cheat|Stop all NextBots from moving only|
|nb_lod_0_limit|12|sv,cheat||
|nb_lod_0_range|1500|sv,cheat||
|nb_lod_1_limit|25|sv,cheat||
|nb_lod_1_range|2500|sv,cheat||
|nb_lod_debug|false|sv,cheat||
|nb_lod_stats|0|sv,cheat||
|nb_move_to_cursor|cmd|sv,cheat|Tell all NextBots to move to the cursor position|
|nb_select|cmd|sv,cheat|Select the bot you are aiming at for further debug operations.|
|nb_stop|false|sv,rep,cheat|Stop all NextBots|
|nb_update_debug|false|sv,cheat||
|nb_update_framelimit|15|sv,cheat||
|nb_update_frequency|0.1|sv,cheat||
|nb_update_maxslide|2|sv,cheat||
|nb_warp_selected_here|cmd|sv,cheat|Teleport the selected bot to your cursor position|
|nemestice_gameplay_tip_number|0|cl,a||
|nemestice_show_game_info|true|cl,a||
|net_async_clientconnect|true||Enable async client connect optimization|
|net_async_job_random_sleep|0||Sleep randomly 0..net_async_job_random_sleep ms in the parallel server jobs; sleep is per job|
|net_captureculldata|cmd||Captures low-level data to replay path culling algorithm behavior in controlled unit test environment|
|net_channels|cmd||Shows net channel info|
|net_connections_stats|cmd||Print detailed network statistics for each network connection|
|net_culloptimization|true||Enable optimization of slow path that makes HLTV CPU consumption high in AnimGraph-using mods. Will switch to this on by default soon.|
|net_debug_to_file|false|sv||
|net_detailed_canpacket_log|false|||
|net_fakelag|cmd||Shorthand for 'net_option FakePacketLag_Recv'|
|net_force_steamdatagram|false|cl,a|If SDR connectivity is possible with gameserver, then always use it, even if GC selected to use ordinary UDP for this match.|
|net_listallmessages|cmd|cheat|List all registered net messages|
|net_log_processing|false||Log network processing|
|net_max_message_process_count|0||Maximum number of messages to process from a client in a single frame (0 == no limit).|
|net_max_message_queue_size|0||Maximum number of messages to allow waiting in queue after processing; exceeding this disconnects the client. 0 == no limit|
|net_max_polymorphic_spew|5||Max polymorphic variants to spew when spewing a flattened serializer.|
|net_maxroutable|1200|a,user|Requested max packet size before packets are 'split'.|
|net_messageinfo|cmd|cheat|Display info about a message (by classname or id)|
|net_option|cmd||Get or set SteamNetworkingSockets options such as fake packet lag and loss|
|net_p2p_listen_dedicated|false||Should dedicated server listen for new-style P2P?|
|net_public_adr|0|release|For servers behind NAT/DHCP meant to be exposed to the public internet, this is the public facing ip address string|
|net_qospacketloss_percentage_threshold|5||Spew a warning if packet loss percentage is above this threshold|
|net_restrict_showmsg_socket|0||If set, only net_showmsg spew for data inbound on this socket name e.g. client, server, etc.|
|net_serializedentitymemory|cmd||Spew CSerializedEntity memory|
|net_serializedentitymetadatainfo|cmd||Spew CSerializedEntity metadata information|
|net_showdrop|false||Show dropped packets in console|
|net_showeventlisteners|false|sv|Show listening addition/removals|
|net_showevents|0|sv|Dump game events to console (1=client only, 2=all).|
|net_showmsg|0||Show incoming message|
|net_showoob|false||Show connectionless UDP traffic.|
|net_showpeaks|0||Show messages for large packets only|
|net_showreliable|0||Like net_showmsg, but only spew reliable messages|
|net_showudp|false|release|Dump UDP packets summary to console|
|net_showudp_remoteonly|true|release|Dump non-loopback udp only|
|net_spewcounts|cmd||Spew serializer counts, client only by default, specify server to spew server counts |
|net_stats_json|cmd||Output server networking statistics in json format|
|net_status|cmd||Shows current network status|
|net_use_packet_compression|true||Compress network traffic|
|net_usesocketsforloopback|false||Use network sockets layer even for listen server local player's packets (multiplayer only).|
|net_validatemessages|cmd|cheat|Activates/deactivates net message validation|
|neutral_camp_arrow_offset|100|cl||
|nextdemo|cmd|release|Play next demo in sequence.|
|nian_fight_duration|1500|sv,cl,rep,cheat||
|noclip|cmd|sv,cheat|Toggle. Player becomes non-solid and flies.  Optional argument of 0 or 1 to force enable/disable|
|noclip_fixup|true|sv,cheat||
|notarget|cmd|sv,cheat|Toggle. Player becomes hidden to NPCs.|
|npc_destroy|cmd|sv,cheat|Removes the given NPC(s) from the universe  Arguments|
|npc_kill|cmd|sv,cheat|Kills the given NPC(s)  Arguments|
|npc_select|cmd|sv,cheat|Select or deselects the given NPC(s) for later manipulation.  Selected NPC's are shown surrounded by a red translucent box  Arguments|
|npc_vphysics|false|sv||
|npcsolve_attract_draw|false|sv||
|npcsolve_constraint_nav|true|sv||
|npcsolve_constraint_npc|true|sv||
|npcsolve_drag_linear|0|sv||
|npcsolve_forward|true|sv||
|npcsolve_forward_const|30000|sv||
|npcsolve_forward_dist|200|sv||
|npcsolve_forward_margin|5|sv||
|npcsolve_path_close_const|0|sv||
|npcsolve_path_close_max_tension|100|sv||
|npcsolve_path_lookahead_const|4|sv||
|npcsolve_path_lookahead_dist|100|sv||
|npcsolve_path_vel_const|0|sv||
|npcsolve_separation|true|sv||
|npcsolve_separation_const|10000|sv||
|npcsolve_separation_dist|5|sv||
|npcsolve_separation_draw|false|sv||
|npcsolve_separation_jitter|0|sv||
|npcsolve_separation_r2|false|sv||
|open_asset|cmd||Opens an asset in it's primary editor of choice. Specify the full path to the asset from the mod directory.|
|openshop_category|cmd|cl|opens shop from clicks on the world shop model, specific tab request|
|option_duck_method|false|cl,a,user,per_user|Input toggle control|
|overwatch_help_shown_once|true|cl,a,per_user||
|p2p_listpeers|cmd||List currently known peers.|
|p2p_ping|cmd|cl|Ping a peer.|
|panorama_debugger_theme|Light|cl,a||
|panorama_dispatch_event|cmd||Dispatch the event defined by the argument string. No creating panel is specified.|
|panorama_dump_symbols|cmd||<ESymbolType> Dump all of the symbols in the Panorama symbol table|
|panorama_early_anim_dispatch|true|cl||
|panorama_focus_world_panels|false|cl,a|when set request key focus when a world panel is enabled|
|panorama_generate_layout_xsd|cmd||Generate the Layout XML Schema Definition for the current run-time (types are dependent on which game DLL is running).|
|panorama_print_cache_status|cmd||Print internal panorama refcounts for every file|
|panorama_show_fps|false|||
|panorama_show_fps_scale|1|||
|panorama_worldpanel_update_cull_distance|1000|cl||
|panorama_worldpanel_update_cull_size_threshold|5|cl||
|panorama_worldpanel_update_culling|false|cl||
|particle_powsimd_random_range_exp|true|||
|particle_profile|cmd||Profile particle|
|particle_profile_spike|cmd||Profile particle spike|
|particle_system_start|cmd|sv|start the specified particle system|
|particle_system_stop|cmd|sv|stop the specified particle system|
|particle_test_attach_attachment|0|sv,cheat|Attachment index for attachment mode|
|particle_test_attach_mode|follow_attachment|sv,cheat|Possible Values|
|particle_test_create|cmd|sv,cheat|Creates the named particle system where the player is looking.  Arguments|
|particle_test_destroy|cmd|sv,cheat|Destroys all particle systems matching the specified name.  Arguments|
|particle_test_file|0|sv,cheat|Name of the particle system to dynamically spawn|
|particle_test_start|cmd|sv,cheat|Dispatches the test particle system with the parameters specified in particle_test_file,  particle_test_attach_mode and particle_test_attach_param on the entity the player is looking at.  Arguments|
|particle_test_stop|cmd|sv,cheat|Stops all particle systems on the selected entities.  Arguments|
|particles_multiplier|1|cheat|Multiply # of rendered particles by this for perf testing|
|password|487157736588707675|a,norecord,server_cant_query|Current server access password|
|path|cmd||Show the filesystem path.|
|pause|cmd|release|Toggle the server pause state.|
|pet_preview_gravity|0.0000000.000000-800.000000|||
|pet_preview_underwater|false|||
|phonemedelay|0|cl|Phoneme delay to account for sound system latency.|
|phonemefilter|0.08|cl|Time duration of box filter to pass over phonemes.|
|phonemesnap|2|cl|Lod at level at which visemes stops always considering two phonemes, regardless of duration.|
|phys2_contact_debug_draw_size|2|||
|phys2_debug_broadphase|0|||
|phys_active|true|sv|Whether PLAYER physics is actively simulated (ie. noclip)|
|phys_async_buoyancy_update|false|sv,cl,rep|If true, buoyancy motion controllers are updated in an async job after the tick has completed.|
|phys_batch_ray_test|0|cl||
|phys_build_bounds|false|||
|phys_build_mass|false|||
|phys_buoyancy_angular_damping_multiplier|1|nf,rep|Multiply water damping for buoyancy affecting angular velocity|
|phys_buoyancy_drag_multiplier|1|nf,rep|Multiply water drag (tries to equalize object velocity with the velocity of the water flow)|
|phys_buoyancy_horizontal_damping_multiplier|0|nf,rep|Multiply water damping for buoyancy affecting linear velocity in the horizontal plane|
|phys_buoyancy_vertical_damping_multiplier|1|nf,rep|Multiply water damping for buoyancy affecting linear velocity in the vertical direction|
|phys_continuous_kinematic_update|0|sv,cl,rep||
|phys_cull_internal_mesh_contacts|false|rep||
|phys_debug_draw|cmd||Set up debug-draw of physics internal state|
|phys_debug_showdefaultmaterial|false|cheat|If enabled, surfaces with default material are highlighted in physics debug geometry.|
|phys_drag_multiplier|1|nf,rep|Multiply air drag|
|phys_dump_filter_body_name|0|||
|phys_dump_filter_solid_only|false|||
|phys_dump_filter_trace_callstack|0|||
|phys_dynamic_scaling|true|sv,cl,rep,cheat||
|phys_expensive_shape_threshold|6|cl,cheat||
|phys_fast_report_contacts|1||when 1, fast path for collision reporting is implemented making triggers faster in some cases|
|phys_fastaddcloneshape|false|||
|phys_highlight_expensive_objects|false|cheat|Highlight expensive physics objects|
|phys_highlight_expensive_objects_strength|0.02|cheat|Highlight expensive physics objects strength|
|phys_impactforcescale|1|sv||
|phys_implicit_integarator|true|nf,rep|Use implicit integrator for gyroscopic forces|
|phys_jiggle_bone_enable|true|||
|phys_joint_teleport|true|sv,cheat|Teleport joint anchors if connected to world|
|phys_length_damping_ratio|2|sv,cheat|Spring damping ratio for length constraint|
|phys_length_frequency|5|sv,cheat|Spring stiffness for length constraint|
|phys_log_updaters|false|sv,cl,rep||
|phys_log_updaters_exclude|weaponpistolriflesurvivorcommon_male|sv,cl,rep||
|phys_log_updaters_include|limbs|sv,cl,rep||
|phys_mark_debug|cmd|sv,cheat|Mark object for debug|
|phys_mesh_notify_force_generic|true|rep||
|phys_mesh_notify_ignore_sdf|true|rep||
|phys_old_contact_draw|false|||
|phys_parallel_islands|false|sv,cl,rep|Enable/Disable Parallel Island Solving|
|phys_position_iterations|2|||
|phys_powered_ragdoll_debug|false|sv,cl,rep||
|phys_pushscale|1|sv,cl,rep||
|phys_reload_immediately|false||Set to 1 to reload resources and reconstruct physics of entities on the fly. May unexpectedly change behavior or crash the game, because game code is generally unaware of underlying resource reloads and may hold references to physics that may become invalid during resource reload. It is inherently harder for physics to deal with resource reloads because of persistent nature of objects being simulated (textures can be easily reloaded on the fly; if an entity holds a handle to a ragdoll body part, it may expect that handle to stay valid while the ragdoll exists)|
|phys_shoot|cmd|sv,cheat|Shoots a phys object.|
|phys_shoot_angular_speed|3600|sv||
|phys_shoot_speed|250|sv||
|phys_show_stats|false|sv,cl,rep||
|phys_skip_creating_trivial_islands|false|rep||
|phys_solve_in_parallel_with_island_build|false|rep||
|phys_stressbodyweights|5|sv||
|phys_threaded_transform_update|false|sv,cl,rep||
|phys_timescale|1|sv|Scale time for physics|
|phys_upimpactforcescale|0.375|sv||
|phys_use_block_solver|true|sv,cheat|Use block solving for constraint entities|
|phys_use_position_based_toi_test|false|nf,rep|Use a position based heuristic to cull slow objects from the TOI phase of the solver|
|phys_validate|false|||
|phys_vehicleimpactforcescale|1.5|sv||
|phys_velocity_iterations|8|||
|phys_visualize_awake_dynamic_only|false|sv,cl,rep||
|phys_visualize_awake_unattached_only|false|sv,cl,rep||
|phys_visualize_traces|false|sv,cl,rep,cheat||
|physcannon_maxforce|1500|sv||
|physcannon_minforce|700|sv||
|physics_debug_entity|cmd|sv|Dumps debug info for an entity|
|physics_hull_sphere_cast_sat_experimental|1|||
|pickup_check_period|0.25|sv||
|ping_wheel_0|0|cl,a,per_user||
|ping_wheel_1|1|cl,a,per_user||
|ping_wheel_2|2|cl,a,per_user||
|ping_wheel_3|3|cl,a,per_user||
|ping_wheel_4|4|cl,a,per_user||
|ping_wheel_5|5|cl,a,per_user||
|ping_wheel_6|6|cl,a,per_user||
|ping_wheel_7|1|cl,a,per_user||
|pixelvis_debug|cmd|cheat|Dump debug info|
|play|cmd|server_can_execute|Play a sound.|
|playcast|cmd||Play a broadcast|
|playdemo|cmd|release|Play a recorded demo file (.dem ).|
|playdemo_scripted|cmd|cl|Play a demo with an associated markup script.|
|player0_using_joystick|false|a||
|player_debug_off_nav|false|sv,cheat||
|player_debug_print_damage|false|sv,cheat|When true, print amount and type of all damage received by player to console.|
|player_item_merge_dots_dist|32|cl||
|playsound|cmd||playsound <soundname>|
|playsoundscape|cmd|cl,cheat|Forces a soundscape to play|
|playvol|cmd||Play a sound at a specified volume.|
|png_screenshot|cmd||Take a .png screenshot|
|pop_var_values|cmd||Restore previously pushed convars and config values|
|population_distribution_debug|0|sv,rep||
|portrait_red|200|cl||
|practice_password|0|cl|Password used to filter private practice lobbies.|
|print_model_bind_pose|cmd||Prints the bind pose of the specified model. Optionally limits to a particular bone and its parent chain, otherwise prints the entire skeleton.|
|progress_enable|cmd|||
|projection_reload_ability_data|cmd|cl|Reload ability_projection.txt|
|prop_debug|cmd|sv,cheat|Toggle prop debug mode. If on, props will show colorcoded bounding boxes. Red means ignore all damage. White means respond physically to damage but never break. Green maps health in the range of 100 down to 1.|
|prop_debug_collision|false|sv,cheat|Highlights props based on their collision group|
|prop_dynamic_create|cmd|sv,cheat|Creates a dynamic prop with a specific .vmdl aimed away from where the player is looking.  Arguments|
|prop_nav_ignore_edge_len|-1|sv||
|prop_nav_ignore_mass|-1|sv||
|prop_nav_obstacle_avoid_mass|100.1|sv||
|prop_nav_obstacle_avoid_use_connection_blocker|false|sv||
|prop_nav_obstacle_block_edge_min_a|-1|sv||
|prop_nav_obstacle_block_edge_min_b|-1|sv||
|prop_nav_obstacle_block_mass_a|-1|sv||
|prop_nav_obstacle_block_mass_b|-1|sv||
|prop_physics_create|cmd|sv,cheat|Creates a physics prop with a specific .vmdl aimed away from where the player is looking.  Arguments|
|proped_debug_priority|false|||
|property_editor_use_overlay|true|||
|props_break_max_pieces_perframe|16|sv,cl,rep|Maximum prop breakable piece count per frame (-1 = model default)|
|push_var_values|cmd||Save convars and config values|
|pvs_debugentity|-1|sv,release|Verbose spew for this entity when doing IsInPVS computation.|
|pvs_flowtype|0|sv,release|Flow through spawn groups for vis (0 == default, 1 == always visible, 2 == never visible.|
|pwatchent|-1|cl,cheat|Entity to watch for prediction system changes.|
|pwatchvar|0|cl,cheat|Entity variable to watch in prediction system for changes.|
|quit|cmd|release,vconsole_set_focus|Quit the game|
|r_add_views_in_pre_output|false|||
|r_AirboatViewDampenDamp|1|sv,cl,nf,rep,cheat||
|r_AirboatViewDampenFreq|7|sv,cl,nf,rep,cheat||
|r_AirboatViewZHeight|0|sv,cl,nf,rep,cheat||
|r_allow_all_objects_to_refract|false|cl,cheat||
|r_allow_refracted_particles|true|cl,cheat||
|r_always_render_all_windows|false||Always force all engine & tools to render|
|r_aoproxy_cull_dist|12||Distance to cull the AO proxy as a factor of size|
|r_aoproxy_min_dist|3|||
|r_aoproxy_min_dist_box|1|||
|r_aspectratio|0|||
|r_cacheSequenceData|true|sv,cl,rep||
|r_camerapos|cmd|linked|Prints out the current camera position + orientation to the console|
|r_character_decal_resolution|1024|||
|r_cleardecals|cmd|cl|Clears all decals|
|r_cpu_light_binner_32bit_shadows|false|||
|r_cpu_light_binner_allow_sun_shadows_on_spots|false|||
|r_cpu_light_binner_default_spec_env_fade_time|1|||
|r_cpu_light_binner_shadow_target_size|3072|||
|r_cpu_light_binner_spot_shadow_size|768|||
|r_cpu_light_binner_use_gpu|true|||
|r_cubemap_debug_colors|0|cheat||
|r_dac_particle_desat_amount|1|cl||
|r_dac_particle_desat_color|1.0000001.0000001.000000|cl||
|r_dashboard_render_quality|false|cl||
|r_debug_precipitation|false|cl,cheat|Show precipitation volumes|
|r_decals|2048|cl||
|r_decals_default_fade_duration|1|cl,rep||
|r_decals_default_start_fade|30|cl,rep||
|r_deferred_additive_pass|false|cl||
|r_deferred_height_fog|false|cl||
|r_deferred_simple_light|0|cl|0=off, 1=on, 2=debug visualization|
|r_deferred_specular|false|cl||
|r_deferred_specular_bloom|false|cl||
|r_depth_of_field|1|cl|0 = off, 1 = Infinity Ward GPU Gems 3 ch 28, 2 = Gustafsson 2018 Reference, 3 = Gustafsson 2018 Precomputed Coc, 4 = Gustafsson 2018 Precomputed Coc and Depth|
|r_directional_lightmaps|true|||
|r_directlighting|true|cheat|Set to use direct lighting|
|r_dither_scale|1|||
|r_dof1_d0|0.2|cl||
|r_dof1_d1|0.3|cl||
|r_dof_override|false|cheat||
|r_dof_override_far_blurry|2000|cheat||
|r_dof_override_far_crisp|180|cheat||
|r_dof_override_near_blurry|-100|cheat||
|r_dof_override_near_crisp|0|cheat||
|r_dof_override_tilt_to_ground|0.5|cheat||
|r_dopixelvisibility|true|cheat||
|r_dosta_allow_spotlight_shadows|true|cl||
|r_dota_allow_colorwarp|true|cl||
|r_dota_allow_desaturate_layers|true|cl||
|r_dota_allow_highquality_shadows|true|cl,cheat||
|r_dota_allow_parallax_mapping|true|cl||
|r_dota_allow_particle_only_portraits|true|cl||
|r_dota_allow_wind_on_trees|false|cl||
|r_dota_always_reflect_refract|false|cl,cheat|1 = force setup of refrect / refact pipelines even when using cheap water|
|r_dota_bloom_compute_shader|1|cl|Use compute shader for Bloom downsample|
|r_dota_caustic_fog_exclusion_radius|3000|cl||
|r_dota_caustic_fog_plane_min|-128|cl||
|r_dota_clouds|true|cl,cheat||
|r_dota_color_correction|true|cl||
|r_dota_debug_reflection_rects|false|cl,cheat||
|r_dota_depthbias|0.001|cl,cheat||
|r_dota_disable_portrait_world_renderer|false|cl||
|r_dota_draw_overlays|true|cl,cheat||
|r_dota_draw_water|true|cl,cheat||
|r_dota_enabled_3d_skybox_postprocess|true|cl||
|r_dota_framebuffer_refraction|true|cl,cheat||
|r_dota_fsr_enable_mip_bias|true|cl|Apply negative mip bias when rendering with FSR.|
|r_dota_fsr_rcas_sharpness|0.25|cl|RCAS sharpness when using FSR + RCAS upsample.|
|r_dota_fsr_upsample|0|cl|0 == bilinear upsampe, 1 == FSR upscample, 2 == FSR + RCAS upsample|
|r_dota_fxaa|false|cl||
|r_dota_height_fog_exclusion_radius|2200|cl||
|r_dota_height_fog_plane_height|128|cl||
|r_dota_highlight_particle_only_portraits|false|cl||
|r_dota_local_light_compute|false|cl||
|r_dota_lowend_objects|1|cl,cheat|0 = Force disable, 1 = use video settings, 2 = force enable|
|r_dota_normal_maps|false|cl||
|r_dota_prewarm_particles|true|cl||
|r_dota_reflection_min_far_plane|5000|cl,cheat||
|r_dota_refract_heroes|false|cl,a||
|r_dota_render_2d_skybox|true|cl||
|r_dota_render_3d_skybox|true|cl||
|r_dota_shadow_ambient_light|1.5|cl||
|r_dota_shadows|true|cl,cheat||
|r_dota_shadows_debug|false|cl,cheat||
|r_dota_shadows_scissor|true|cl||
|r_dota_slopescaledepthbias|4.5|cl,cheat||
|r_dota_spotlight_shadows_resolution|256|cl||
|r_dota_tonemap|true|cl||
|r_dota_tools_full_renderer|true|cl,cheat||
|r_dota_ultra_slopescaledepthbias|4.5|cl,cheat||
|r_dota_unseen_fow|true|cl,cheat||
|r_dota_water_reflection|true|cl,cheat||
|r_dota_water_refraction|true|cl,cheat||
|r_dota_white_skybox|false|cl,cheat||
|r_dota_wind_min_high_freq_strength|25|cl||
|r_draw3dskybox|true|cl||
|r_draw_first_tri_only|false|cheat||
|r_draw_instances|true|cheat||
|r_draw_overlays|true|||
|r_draw_particle_children_with_parents|-1|cheat|Draw particle children with parents (-1=use gameinfo, 0=no, 1=yes)|
|r_draw_selected_ring|true|cl,a|hides the selected_ring particle|
|r_drawblankworld|false|cheat|Render blank instead of the game world|
|r_drawdecals|true|cheat|Set to render decals|
|r_drawdevvisualizers|false|cl,cheat|Render dev visualizers|
|r_drawmodeldecals|true|cl||
|r_drawpanorama|true|cheat|Enable the rendering of panorama UI|
|r_drawparticles|true|cheat|Enable/disable particle rendering|
|r_drawpixelvisibility|false||Show the occlusion proxies|
|r_drawropes|true|cl,cheat||
|r_drawskybox|true|cheat|Render the 2d skybox.|
|r_drawsprites|true|cl,cheat||
|r_drawtracers|true|cl,cheat||
|r_drawtracers_firstperson|true|cl||
|r_drawviewmodel|true|cl,cheat|Render view model|
|r_drawworld|true|cheat|Render the world.|
|r_dx11_report_live_objects|cmd||Prints out live D3D11 objects (requires -dx11debug)|
|r_dx11_software_cmd_lists|true||Enable Software Command lists for DX11 (Avoid using deferred contexts)|
|r_entpos|cmd|linked|Moves the camera position + orientation to the named entity|
|r_experimental_lag_limiter|false|||
|r_extra_render_frames|0|cheat||
|r_fallback_texture_lod_scale|2|cheat|Scale factor for requested texture size (texture streaming) - used for geo that doesn't have a precomputed UV density measure|
|r_farz|-1|cl,cheat|Override the far clipping plane. -1 means to use the value in env_fog_controller.|
|r_flashlightambient|0|cl,cheat||
|r_flashlightbacktraceoffset|0.4|cl,cheat||
|r_flashlightbrightness|1|cl,rep,cheat||
|r_flashlightconstant|0|cl,rep,cheat||
|r_flashlightfar|1500|cl,rep,cheat||
|r_flashlightfov|53|cl,rep,cheat||
|r_flashlightladderdist|40|cl,cheat||
|r_flashlightlinear|100|cl,rep,cheat||
|r_flashlightlockposition|false|cl,cheat||
|r_flashlightmuzzleflashfov|120|cl,cheat||
|r_flashlightnear|4|cl,rep,cheat||
|r_flashlightnearoffsetscale|1|cl,cheat||
|r_flashlightoffsetforward|0|cl,rep,cheat||
|r_flashlightoffsetright|5|cl,rep,cheat||
|r_flashlightoffsetup|-5|cl,rep,cheat||
|r_flashlightquadratic|0|cl,rep,cheat||
|r_flashlightshadowatten|0.35|cl,cheat||
|r_flashlighttracedistcutoff|128|cl,cheat||
|r_flashlighttracedistwatercutoff|80|cl,cheat||
|r_flashlightvisualizetrace|false|cl,cheat||
|r_force_engine_render_frame|cmd||Force a single render of the engine viewport.|
|r_force_no_present|false|cheat|Force the render device to not present frames.|
|r_force_zprepass|-1|cheat|0|
|r_frame_sync_enable|true|||
|r_freeze_sceneobjects|false|cl||
|r_freezeparticles|false|cheat|Pause particle simulation|
|r_fullscreen_gamma|2.2|a|Screen Gamma (only in fullscreen modes)|
|r_gpu_mem_stats|cmd|linked|Display GPU memory usage.|
|r_grass_allow_flattening|false|||
|r_grass_alpha_test|0|||
|r_grass_density_mode|0||0 = Density corresponds to blade existance, 1 = Density corresponds to blade height, 2 = Both 0 and 1|
|r_grass_end_fade|3000|||
|r_grass_max_brightness_change|75|||
|r_grass_parallel_load|false|||
|r_grass_quality|0||0 = Off, 1 = Low, 2 = Med, 3 = high, 4 = ultra|
|r_grass_start_fade|2000|||
|r_grass_vertex_lighting|0|||
|r_hero_debug_render_mode|0|cl,cheat|Hero Debug Rendering|
|r_impacts_alt_orientation|true|cl||
|r_impacts_decal_grazing_incidence_cutoff|0.55|cl||
|r_impacts_decal_grazing_incidence_variance|0.1|cl||
|r_incrementlodscale|cmd|linked|Modifies the LOD scale|
|r_indirectlighting|true|cheat|Set to use indirect lighting|
|r_JeepViewDampenDamp|1|sv,cl,nf,rep,cheat||
|r_JeepViewDampenFreq|7|sv,cl,nf,rep,cheat||
|r_JeepViewZHeight|10|sv,cl,nf,rep,cheat||
|r_light_flickering_enabled|true|sv,cl,rep||
|r_light_probe_volume_debug_colors|0|cheat||
|r_light_probe_volume_debug_grid|false|cheat|Show LPV debug grid, 0|
|r_light_probe_volume_debug_grid_albedo|128128128|cheat|albedo for LPV debug grid|
|r_light_probe_volume_debug_grid_bbox|true|cheat|Show LPV bounding box when debug grid is on, 0|
|r_light_probe_volume_debug_grid_metalness|0|cheat|metalness for LPV debug grid|
|r_light_probe_volume_debug_grid_prim|0|cheat|0|
|r_light_probe_volume_debug_grid_roughness|0.5|cheat|roughness for LPV debug grid|
|r_light_probe_volume_debug_grid_samplesize|4|cheat|sphere radius (world) for LPV debug grid|
|r_lightBinnerFarPlane|4096|cheat||
|r_lightmap_set|lightmaps|cheat|Lightmap set to use, only works on map load|
|r_lightmap_size|65536||Maximum lightmap resolution.|
|r_lightmap_size_directional_irradiance|-1||Maximum lightmap resolution for directional_irradiance channel. -1 = use value of r_lightmap_size|
|r_low_latency|1||NVIDIA Low Latency (0 = off, 1 = on, 2 = on + boost)|
|r_low_latency_trigger_flash|true||NVIDIA Low Latency Trigger Flash|
|r_mapextents|1444|cl,cheat|Set the max dimension for the map.  This determines the far clipping plane|
|r_max_texture_pool_size|0||Upper limit on texture pool size.|
|r_mixed_shadows_fade_in_time|0.5|sv,cl,rep||
|r_mixed_shadows_fade_out_time|0.5|sv,cl,rep||
|r_morphing_enabled|true|cheat||
|r_multigpu_num_gpus_found|1|||
|r_multigpu_num_gpus_used|1|||
|r_muzzleflashbrightness|0.4|cl,rep,cheat||
|r_muzzleflashlinear|0.05|cl,rep,cheat||
|r_nearz|-1|cl,cheat|Override the near clipping plane. -1 means use the default.|
|r_particle_cables_cast_shadows|true|||
|r_particle_debug_filter|0||Limit debug visualizations to substring match of effect name|
|r_particle_debug_force_simulation|0||-1 for all asleep, 1 for all awake|
|r_particle_debug_randomseeds|false||Use random seeds in debug|
|r_particle_force_material_binds|false|||
|r_particle_gpu_implicit|true|||
|r_particle_max_detail_level|3||The maximum detail level of particle to create|
|r_particle_max_draw_distance|1000000.000000|cheat|The maximum distance that particles will render|
|r_particle_max_texture_layers|-1|||
|r_particle_min_timestep|0||A minimum on particle simulation time, particle simulation happening more frequently than this will lerp.|
|r_particle_render_test|false||render particles 100 times and show perf|
|r_particle_timescale|1|||
|r_pipeline_stats_command_flush|false||Experimental|
|r_pipeline_stats_flush_before_sleeping|false||Experimental|
|r_pipeline_stats_present_flush|false||Experimental|
|r_pipeline_stats_use_flush_api|true||Experimental|
|r_pixelvisibility_partial|true|cheat||
|r_pixelvisibility_spew|false|cheat||
|r_print_texture_stats|cmd||Texture stats|
|r_printdecalinfo|cmd|cl|Prints info about decals currently in the scene|
|r_propsmaxdist|1200|cl|Maximum visible distance|
|r_RainAllowInSplitScreen|false|cl|Allows rain in splitscreen|
|r_RainParticleDensity|1|cl|Density of Particle Rain 0-1|
|r_render_coordination_state|cmd||Prints out the current render coordination state.|
|r_render_to_cubemap_debug|false|||
|r_render_world_node_bounds|false|cheat|Render world node bounds|
|r_renderdoc_capture_frame|cmd|linked|Triggers a RenderDoc capture|
|r_renderdoc_open_captures|true|||
|r_rendersun|true|cheat|Render sun lighting|
|r_replay_post_effect|-1|cl,cheat||
|r_reset_character_decals|false|||
|r_ropetranslucent|true|cl||
|r_screen_size_expansion|0|cl||
|r_setpos|cmd|linked|Moves the camera position + orientation to the specified position|
|r_shadows|true|cheat||
|r_show_hipoly_draw_calls|0|cheat|Transparent wireframe overlay for draw calls with triangle count higher than specified number|
|r_showdebugoverlays|false|cheat|Set to render debug overlays|
|r_showdebugrendertarget|false|cheat|Set the debug render target to show, 0 == disable|
|r_showsceneobjectbounds|false|cheat|Show scenesystem object bounding boxes|
|r_showsunshadowdebugrendertargets|false|cheat|Set to render sun shadow render targets|
|r_showsunshadowdebugsplitvis|false|cheat|Set to render sun shadow split visibility debugger|
|r_size_cull_threshold_shadow|0.2|cheat|Threshold of sun shadow map size percentage below which objects get culled|
|r_skinning_enabled|true|cheat||
|r_skip_particle_light_bounds_in_forward|true|cl||
|r_skip_precache_validation_check|true|||
|r_smooth_morph_normals|true|||
|r_ssao|false||Set to use screen-space ambient occlusion|
|r_ssao_bias|0.5|||
|r_ssao_blur|true|||
|r_ssao_radius|30|||
|r_ssao_strength|1.2|||
|r_stereo_multiview_instancing|false|cheat|Use multiview instancing for stereo rendering.|
|r_strip_invisible_during_sceneobject_update|false|cl||
|r_suppress_redundant_state_changes|true|||
|r_test_econ_item_isolate_view|false|cl||
|r_texture_budget_dynamic|true||Dynamically adjust texture streaming budget based on GPU memory usage.|
|r_texture_budget_threshold|0.9||Reduce texture memory pool size when this percentage of the budget is full.|
|r_texture_budget_update_period|0.5||Time (in seconds) between updating texture memory budget.|
|r_texture_eager_eviction|false|||
|r_texture_hookup_uses_threadpool|true||Async Texture hookup uses its own threadpool instead of the global pool.|
|r_texture_lod_scale|1|cheat|Scale factor for requested texture size (texture streaming)|
|r_texture_nonstreaming_load|true||Allow immediately loading mips of textures (when possible) when their headers are loaded, saving IO & reducing latency.|
|r_texture_pool_increase_rate|64||Increase texture memory pool size by this many MB / s when under budget.|
|r_texture_pool_reduce_rate|256||Reduce texture memory pool size by this many MB / s when over budget.|
|r_texture_pool_size|3213||Total size of the texture pool in MB|
|r_texture_stream_max_resolution|-1||Maximum resolution for top mip level in streaming textures. -1 = ignored.|
|r_texture_stream_mip_bias|0||Biases the mip level the texture streaming system choses to stream for each texture.|
|r_texture_stream_resolution_bias|1|||
|r_texture_stream_resolution_bias_decrease_rate|0.1|||
|r_texture_stream_resolution_bias_increase_rate|0.05|||
|r_texture_stream_resolution_bias_min|1|||
|r_texture_stream_resolution_bias_update_period|0.5|||
|r_texture_stream_throttle_amount|10|||
|r_texture_stream_throttle_count|10|||
|r_texture_stream_throttle_count_over_budget|1|||
|r_texture_streaming_timesliced|true|||
|r_texture_streamout_unthrottle_ms|0.2||After hitting throttling limits for streamout, allow it to continue up to this number of milliseconds.|
|r_texturefilteringquality|3||0|
|r_textures_evict_all|cmd|linked|Evict all resident texture.|
|r_threaded_particles|true|||
|r_threaded_scene_object_update|true|cl||
|r_timestamp_query_multiplier|1||Set the TIMESTAMP query cycle multiplier, for drivers that lie|
|r_toggleviewportsize|cmd||Toggles viewport size between small + full window.|
|r_translucent|true|cheat|Enable rendering of translucent geometry|
|r_use_memory_budget_model|false||Use a model of GPU memory use to determine budget rather than querying the OS.|
|r_validate_texture_streaming|false||Dumps state of texture streaming at the next frame boundary.|
|r_vconsole_foregroundforcerender|true||When VConsole is in the foreground, force all engine & tools to render|
|r_viewport|cmd||Slams viewport size to a specified value.|
|r_wait_on_present|false|||
|r_world_allow_bindless_desc|true|||
|r_world_frame_load_threshold_ms|10|||
|r_world_wind_dir|0.7070000.7070000.000000|||
|r_world_wind_frequency_grass|0.03|||
|r_world_wind_frequency_trees|0.003|||
|r_world_wind_offset_speed|0.2500000.3000000.200000|||
|r_world_wind_smooth_time|2|||
|r_world_wind_strength|40|||
|r_worldlod|true|cheat|Set to enable world LOD|
|r_zprepass_normals|false|cheat|0|
|ragdoll_debug_item_detachment|false|sv,rep||
|ragdoll_impact_strength|500|cl||
|ragdoll_lru_debug_removal|false|sv,cl,rep,cheat||
|ragdoll_lru_min_age|10|sv,cl,rep,cheat||
|ragdoll_override_root_orientation|true|sv,rep||
|ragdoll_prop_settle|true|sv,rep|Enable more aggressive ragdoll settling|
|ragdoll_prop_sleepaftertime|4|sv,rep|After this many seconds of being basically stationary, the ragdoll will go to sleep.|
|ragdoll_prop_sleepdisabletime|1.5|sv,rep|Ragdoll is not allowed to physically sleep until this timer has elapsed.|
|ragdoll_relax_limts|false|sv,rep||
|ragdoll_scale_sleep_tolerance|true|sv,rep||
|ragdoll_validate_targetpose|true|sv,rep||
|ragdoll_visualize_creation_skeleton|false|sv,rep||
|ragdoll_visualize_targetpose|false|sv,rep||
|rangefinder|cmd|sv,cheat|Measures distance along a ray|
|rate|1239090|a,user|Min bytes/sec the host can receive data|
|ray_bench|cmd|sv|Load the rays and run the benchmark|
|rc_default_texture_encode_quality|0||Texture compression quality used in tools mode|
|rc_default_texture_encode_rdo_lambda|0||Texture compression RDO lambda used in tools mode|
|rc_relaxedcones_cpu|false|||
|rcon|cmd|norecord,release|Issue an rcon command.|
|rcon_address|0|norecord,release,server_cant_query|Address of remote server if sending unconnected rcon commands (format x.x.x.x|
|rcon_connected_clients_allow|true|rep,release|Allow clients to use rcon commands on server.|
|rcon_password|0|norecord,release,server_cant_query|remote console password.|
|recast_mark_overhang|true|rep,cheat|Enable/disable overhang detection|
|recast_partitioning|0|rep,cheat|0 = watershed, 1 = monotone, 2 = layers|
|record|cmd|norecord,release|Record a demo.|
|reload_model|cmd||Force a reload of a vmdl resource|
|reloadgame|cmd|cheat,vconsole_set_focus|Reload the most recent saved game.|
|remove_weapon|cmd|sv,cheat|Remove a weapon held by the player.  Arguments|
|removeid|cmd||Remove a user ID from the ban list.|
|removeip|cmd||Remove an IP address from the ban list.|
|repeat_last_console_command|cmd|release|Repeat last console command.|
|replay_death|cmd|sv,cheat|start hltv replay of last death|
|replay_debug|0|rep,release||
|replay_start|cmd|sv,cheat|Start GOTV replay|
|replay_stop|cmd|sv|stop hltv replay|
|report_cliententitysim|false|cl,cheat|List all clientside simulations and time - will report and turn itself off.|
|report_clientthinklist|false|cl,cheat|List all clientside entities thinking and time - will report and turn itself off.|
|report_connection_failure_percentage|0|||
|report_soundpatch|cmd|sv|reports sound patch count|
|reset_gameconvars|cmd|cheat|Reset game convars to default values|
|resource_leaks|cmd||resource_leaks <resource_name>|
|resource_list|cmd||List loaded resources matching a substring|
|resource_log_allocate_timing|cmd||Log time spent in Allocate for all resource types|
|resource_manifest_validate_modules|cmd||Scan all of the loaded modules and validate any resource manifests found|
|resource_repeated_reload|cmd||resource_repeated_reload <count> <resource_name> (<resource name> ...)|
|resource_reset_allocate_timing|cmd||Reset tracked time spent in Allocate (see resource_log_allocate_timing)|
|resourcecompiler_log_compile_stats|false|||
|respawn_player|cmd|sv,cheat|Respawns the player from death! |
|restart|cmd|cheat,vconsole_set_focus|Poor man's restart|
|rope_averagelight|true|cl|Makes ropes use average of cubemap lighting instead of max intensity.|
|rope_collide|1|cl|Collide rope with the world|
|rope_shake|false|cl||
|rope_smooth_enlarge|1.4|cl|How much to enlarge ropes in screen space for antialiasing effect|
|rope_smooth_maxalpha|0.5|cl|Alpha for rope antialiasing effect|
|rope_smooth_maxalphawidth|1.75|cl||
|rope_smooth_minalpha|0.2|cl|Alpha for rope antialiasing effect|
|rope_smooth_minwidth|0.3|cl|When using smoothing, this is the min screenspace width it lets a rope shrink to|
|rope_subdiv|2|cl|Rope subdivision amount|
|rope_wind_dist|1000|cl|Don't use CPU applying small wind gusts to ropes when they're past this distance.|
|rpestats|cmd||dump rpe|
|rr_dacmode|false|sv,cl,rep|If set to 1, enable special functionality for DAC|
|rr_debugclassname|0|sv,cl,rep|If set, rr_debugclassname will print only response tests where 'classname' corresponds to this variable. Use to filter for a specific character.|
|rr_debugresponseconcept|0|sv,cl,rep|If set, rr_debugresponseconcept will print only responses testing for the specified concept|
|rr_debugresponses|0|sv,cl,rep|Show verbose matching output (1 for simple, 2 for rule scoring, 3 for noisy). If set to 4, it will only show response success/failure for npc_selected NPCs.|
|rr_debugrule|0|sv,cl,rep|If set to the name of the rule, that rule's score will be shown whenever a concept is passed into the response rules system.|
|rr_dumpresponses|false|sv,cl,rep|Dump all response_rules.txt and rules (requires restart)|
|rr_findrules|cmd|sv|Search and list rules by substring.|
|rr_findrules_verbose|cmd|sv|Search and list rules by substring.|
|rr_followup_maxdist|1800|sv,cheat|'then ANY' or 'then ALL' response followups will be dispatched only to characters within this distance.|
|rr_forceconcept|cmd|sv,cheat|fire a response concept directly at a given character. USAGE|
|rr_reloadresponsesystems|cmd|sv,cheat|Reload all response system scripts.|
|rr_thenany_score_slop|0|sv,a,cheat|When computing respondents for a 'THEN ANY' rule, all rule-matching scores within this much of the best score will be considered.|
|rtx_force_default_hitgroup|false||Forces all ray traced geometry to use default hit shaders instead of specialized ones.|
|rubikon_joint_always_draw_at_pivot_point|true|||
|rubikon_joint_deepdebugging|false|||
|run_perftest|cmd|cheat,norecord|Execute perftest.cfg|
|save|cmd|sv,norecord|Save Game|
|save_animgraph_recording|cmd|sv,cheat|Saves all active animgraph recordings to disk|
|save_async|true|sv||
|save_clear_subdirectory|cmd|sv,rep||
|save_fake_hitch|0|sv|Force a busy wait for the specified number of milliseconds during save to simulate a hitch|
|save_finish_async|cmd|sv||
|save_history_count|1|sv|Keep this many old copies in history of autosaves and quicksaves.|
|save_maxarray_spew|10|sv,release|Max number of array entries to spew when using SaveRestoreIO spewing.|
|save_screenshot|2|sv|0 = none, 1 = non-autosave, 2 = always, 3 = bug_only|
|save_set_subdirectory|cmd|sv,rep||
|save_showelapsedtime|cmd|sv|display up-to-date elapsed play time|
|save_spew|false|sv,cl,rep||
|save_watchclass|cmd|sv|Restrict spew to entities with matching classname|
|save_watchentity|cmd|sv|Restrict spew to entity index|
|say|cmd|sv|Display player message|
|say_team|cmd|sv|Display player message to team|
|sc_aggregate_gpu_culling|true||Toggles GPU culling of aggregate meshes|
|sc_aggregate_gpu_occlusion_culling|true|||
|sc_allow_dithered_lod|true||Allow use of dithered lod transitions|
|sc_allow_dynamic_constant_batching|true|||
|sc_allow_precomputed_vismembers|true|||
|sc_allow_secondary_contexts|true|||
|sc_batch_layer_cb_updates|true|||
|sc_bounds_group_cull|true|||
|sc_cache_envmap_lpv_lookup|true|||
|sc_check_world|false|cheat||
|sc_clutter_density_full_size|0.05||Screen-size where clutter will be full density|
|sc_clutter_density_none_size|0.01||Screen-size where clutter will be gone|
|sc_disable_baked_lighting|false|||
|sc_disable_culling_boxes|false|cheat||
|sc_disable_procedural_layer_rendering|false|cheat||
|sc_disable_shadow_fastpath|false|cheat||
|sc_disable_shadow_materials|false|cheat||
|sc_disable_spotlight_shadows|false|cheat||
|sc_disable_world_materials|false|cheat||
|sc_disableThreading|false|cheat||
|sc_dithered_lod_transition_amt|0.075||Percentage of the transition between two lods we will apply a dither|
|sc_dump_lists|false|cheat||
|sc_dumpworld|cmd|cheat|Dump a list of the objects in a sceneworld (Usage|
|sc_dumpworld3d|cmd|cheat|Dump the objects in a sceneworld into a 3d geoview buffer (Usage|
|sc_enable_discard|true|||
|sc_extended_stats|false|cheat||
|sc_force_lod_level|-1|cheat||
|sc_force_materials_batchable|false|cheat||
|sc_force_push_constant_update_every_draw|false|||
|sc_force_single_display_list_per_layer|false|||
|sc_force_translation_in_projection|false|cheat|If enabled, the camera's translation will be included in the projection matrix.|
|sc_hdr_enabled_override|-1||Override default setting for HDR rendering. -1 default, 0 NoHdr, 1 Hdr, 2 Hdr 1010102 3 Hdr 111110|
|sc_keep_all_layers|false|||
|sc_layer_batch_threshold|128|||
|sc_layer_batch_threshold_fullsort|80|||
|sc_list_extradata_allocations|cmd||Prints out the overall extra data allocation counts|
|sc_listworlds|cmd|cheat|List all the active sceneworlds|
|sc_lod_distance_scale_override|-1|cheat||
|sc_log_submits|false|cheat|Log out display list submits from scenesystem|
|sc_max_framebuffer_copies_per_layer|1|||
|sc_mesh_backface_culling|true|||
|sc_new_morph_atlasing|true|||
|sc_no_cull|false|||
|sc_no_vis|false|||
|sc_only_render_opaque|false|cheat||
|sc_only_render_shadowcasters|false|cheat||
|sc_override_shadow_fade_max_dist|-1|cheat||
|sc_override_shadow_fade_min_dist|-1|cheat||
|sc_parallel_render_a_view|false|||
|sc_queue_reflection_views_to_layers|true|||
|sc_reject_all_objects|false|cheat||
|sc_setclassflags|cmd|cheat|Low level command to set the flags byte associated with an object class. sc_SetClassFlags <classname> <value> |
|sc_shadow_depth_bias|256|||
|sc_shadow_depth_bias_clamp|0|||
|sc_shadow_depth_bias_state_override|false|||
|sc_shadow_slopescale_depth_bias|2.13|||
|sc_show_rejected_objects|0|||
|sc_show_rejected_objects_range|-1|||
|sc_showclasses|cmd|cheat|List the object class names known by scenesystem |
|sc_skip_identical_rt_binds|false|||
|sc_skip_traversal|false|cheat||
|sc_spew_cmt_usage|false|||
|sc_throw_away_all_layers|false|||
|sc_use_clear_subrect|false|||
|sc_visualize_batches|0||color per batch|
|sc_visualize_sceneobjects|0||1 = visualize bounds, 2 = visualize sceneobject mesh materials, 3 = required texture size, 4 = bounds group, 5 = LOD, 6 == LPV Binding|
|scene_clientflex|true|sv,cl,rep|Do client side flex animation.|
|scene_flush|cmd|sv|Flush all .vcds from the cache and reload from disk.|
|scene_maxcaptionradius|1200|sv|Only show closed captions if recipient is within this many units of speaking actor (0==disabled).|
|scene_playvcd|cmd|sv,cheat|Play the given VCD as an instanced scripted scene.|
|scene_print|0|sv,cl,rep|When playing back a scene, print timing and event info to console.|
|scene_vcdautosave|false|cl|Create a savegame before VCD playback|
|screenmessage_notifytime|8|sv|How long to display screen message text|
|screenmessage_show|-1|cheat|Enable display of console messages on screen. 1 = Enabled, 0 = Disabled, -1 = Enabled if vgui is not present|
|screenshot|cmd||Take a screenshot|
|screenshot_height|-1||Screenshot height. -1 for screen height.|
|screenshot_prefix|shot||Set the screenshot auto naming prefix.|
|screenshot_subdir|screenshots||Set the screenshot directory.|
|screenshot_width|-1||Screenshot width. -1 for screen width.|
|script_add_debug_filter|cmd|sv,cheat|Add a filter to the game debug overlay|
|script_add_watch|cmd|sv,cheat|Add a watch to the game debug overlay|
|script_add_watch_pattern|cmd|sv,cheat|Add a watch to the game debug overlay|
|script_attach_debugger|cmd|sv,cheat|Connect the vscript VM to the script debugger|
|script_attach_debugger_at_startup|false|sv||
|script_break_in_native_debugger_on_error|false|sv||
|script_clear_watches|cmd|sv,cheat|Clear all watches from the game debug overlay|
|script_debug|cmd|sv,cheat|Toggle the in-game script debug features|
|script_dump_all|cmd|sv,cheat|Dump the state of the VM to the console|
|script_find|cmd|sv,cheat|Find a key in the VM |
|script_help|cmd|sv,cheat|Output help for script functions|
|script_help2|cmd|sv|Output help for script functions suitable for auto-completion|
|script_reload|cmd|sv,cheat|Reload scripts|
|script_reload_code|cmd|sv,cheat|Execute a vscript file, replacing existing functions with the functions in the run script|
|script_reload_entity_code|cmd|sv,cheat|Execute all of this entity's VScripts, replacing existing functions with the functions in the run scripts|
|script_remove_debug_filter|cmd|sv,cheat|Remove a filter from the game debug overlay|
|script_remove_watch|cmd|sv,cheat|Remove a watch from the game debug overlay|
|script_remove_watch_pattern|cmd|sv,cheat|Remove a watch from the game debug overlay|
|script_resurrect_unreachable|cmd|sv,cheat|Use the garbage collector to track down reference cycles|
|script_trace_disable|cmd|sv,cheat|Turn off a particular trace output by file or function name|
|script_trace_disable_all|cmd|sv,cheat|Turn off all trace output|
|script_trace_disable_key|cmd|sv,cheat|Turn off a particular trace output by table/instance|
|script_trace_enable|cmd|sv,cheat|Turn on a particular trace output by file or function name|
|script_trace_enable_all|cmd|sv,cheat|Turn on all trace output|
|script_trace_enable_key|cmd|sv,cheat|Turn on a particular trace output by table/instance|
|scripted_demo_restart|cmd|cl|Play a demo with an associated markup script.|
|scrubber|cmd||Scrub system off - not a dev build|
|sdr|cmd||An old command that has been renamed to 'net_option'|
|sensitivity|1.25|cl,a,per_user|Mouse sensitivity.|
|server_game_time|cmd|sv|Gives the game time in seconds (server's curtime)|
|server_gc_status|cmd|sv|Check status of connection to the GC|
|servercfgfile|server.cfg|sv,release||
|servervoice_clear|cmd|cl|servervoice_clear|
|servervoice_dump|cmd|cl|servervoice_dump|
|setang|cmd|sv,cheat|Snap player eyes to specified pitch yaw <roll|
|setang_exact|cmd|sv,cheat|Snap player eyes and orientation to specified pitch yaw <roll|
|setinfo|cmd|clientcmd_can_execute|Adds a new user info value|
|setmodel|cmd|sv,cheat|Changes's player's model|
|setpause|cmd|release|Set the pause state of the server.|
|setpos|cmd|sv,cheat|Move player to specified origin (must have sv_cheats).|
|setpos_exact|cmd|sv,cheat|Move player to an exact specified origin (must have sv_cheats).|
|setpos_player|cmd|sv,cheat|Move specified player to specified origin (must have sv_cheats).|
|sf_loadout_rotate_drag|0.19|cl||
|sf_loadout_rotate_frametime_multiplier|8|cl||
|sf_loadout_rotate_grab_scale|0.5|cl||
|sf_loadout_rotate_scale|2|cl||
|shake|cmd|sv,cheat|Shake the screen.|
|shake_show|false|cl|Displays a list of the active screen shakes.|
|shake_stop|cmd|cl,cheat|Stops all active screen shakes. |
|shake_testpunch|cmd|cl,cheat|Test a punch-style screen shake. |
|shop_nav_to_search|cmd|cl|with the shop open, makes the search box active|
|shop_nav_to_tab|cmd|cl|switch to a particular shop tab ( 0 - 12 )|
|shop_select_itemrow|cmd|cl|buy ( or set quickbuy with shift held ) a particular displayed row|
|show_sf_shop|cmd|cl|show shop|
|show_tool|cmd||Show or launch the specified engine tool|
|show_visibility_boxes|false|cl,cheat|Enable or Disable debug display of visibility boxes|
|showconsole|cmd|norecord,release|Show the console.|
|+showitems|cmd|cl||
|+showscores|cmd|cl||
|showtriggers|cmd|sv,cheat|Enable or Disable showing trigger entities|
|showtriggers_toggle|cmd|sv,cheat|Displays the movement bounding box for the triggers in orange.  Some entites will also display entity specific overlays.  Arguments|
|silence_dsp|false|cheat|When on, silences all DSP mixes.|
|sk_autoaim_mode|1|sv,cl,a,rep||
|sk_player_arm|1|sv||
|sk_player_chest|1|sv||
|sk_player_head|2|sv||
|sk_player_leg|1|sv||
|sk_player_stomach|1|sv||
|skel_constraints_enable|true|rep,cheat||
|skel_debug|0|sv,cl,rep||
|skeleton_instance_scaleset_enable|true|sv,cl,rep,cheat||
|skeleton_instance_smear_boneflags|false|sv,cheat|Smear boneflags across the model.  Costs computation, but tests to make sure your bone flags are consistent.|
|skill|1|sv,cl,a,rep,per_user|Game skill level.|
|slot0|cmd|cl,server_can_execute||
|slot1|cmd|cl,server_can_execute||
|slot10|cmd|cl,server_can_execute||
|slot2|cmd|cl,server_can_execute||
|slot3|cmd|cl,server_can_execute||
|slot4|cmd|cl,server_can_execute||
|slot5|cmd|cl,server_can_execute||
|slot6|cmd|cl,server_can_execute||
|slot7|cmd|cl,server_can_execute||
|slot8|cmd|cl,server_can_execute||
|slot9|cmd|cl,server_can_execute||
|smoothstairs|true|sv,cl,rep|Smooth player eye z coordinate when traversing stairs.|
|snapto|cmd|cl||
|snd_arrangement_start|cmd|cheat|Starts the specified arrangement.|
|snd_async_flush|cmd||Flush all unlocked async audio data|
|snd_async_showmem|cmd||Show async memory stats|
|snd_async_showmem_music|cmd||Show async memory stats for just non-streamed music|
|snd_async_showmem_summary|cmd||Show brief async memory stats|
|snd_async_spew_blocking|0||Spew message to console any time async sound loading blocks on file i/o.|
|snd_autodetect_latency|true|a||
|snd_boxverb_simd|true||Enable SIMD code path for shoebox reverb processor.|
|snd_boxverb_simd_svf|1||0 = use biquad instead of svf, 1 = use vectorized svf, 2 = use scalar svf|
|snd_break_on_start_soundevent|0|sv,cl,rep,cheat|Use to debug break on any soundevent that is started matching this name|
|snd_cast|cmd|cheat|Casts a ray and starts a sound event where the ray hits. The sound event will retrigger periodically if cl_snd_cast_retrigger is set. The sound event will clear previous snd_cast events if cl_snd_cast_clear is set. Usage|
|snd_compare_KV_convert|false|||
|snd_compare_soundevents|cmd|cheat|Compare the compiled and loaded contents of 2 soundevents.|
|snd_delay_sound_ms_max|250||Sound device synchronization max delay (ms)|
|snd_delay_sound_ms_shift|23||Sound device synchronization shift (ms)|
|snd_diffusor_simd|false||Enable SIMD code path for diffusor processor.|
|snd_disable_mixer_duck|false|cheat||
|snd_disable_mixer_solo|false|cheat||
|snd_dsp_distance_max|2000|cheat||
|snd_dsp_distance_min|20|cheat||
|snd_duckerattacktime|0.5|a||
|snd_duckerreleasetime|2.5|a||
|snd_duckerthreshold|0.15|a||
|snd_ducktovolume|0.55|a||
|snd_enable_subgraph_corenull_passthrough|true|||
|snd_enable_subgraph_log|false|||
|snd_envelope_rate|0.9|cheat||
|snd_filter|0|cheat||
|snd_foliage_db_loss|0|sv,cheat|foliage dB loss per 1200 units|
|snd_front_headphone_position|cmd||Specifies the position (in degrees) of the virtual front left/right headphones.|
|snd_front_stereo_speaker_position|cmd||Specifies the position (in degrees) of the virtual front left/right speakers.|
|snd_front_surround_speaker_position|cmd||Specifies the position (in degrees) of the virtual front left/right speakers.|
|snd_gain|1|a||
|snd_gain_max|1|cheat||
|snd_gain_min|0.01|cheat||
|snd_gamevoicevolume|0|a|Game v.o. volume|
|snd_gamevolume|0.154391|a|Game volume|
|snd_get_physics_surface_properties|cmd|cheat|Get physics surface properties for all the materials.|
|snd_headphone_pan_exponent|cmd||Specifies the exponent for the pan xfade from phone to phone if the 'exp' pan law is being used.|
|snd_headphone_pan_radial_weight|cmd||Apply cos(angle) * weight before pan law|
|snd_list|0|cheat||
|snd_list_deferred_soundevents|cmd|cheat|List all current deferred load soundevents|
|snd_list_soundevents|cmd|cheat|List all available soundevents|
|snd_list_soundevents_by_stack|cmd|cheat|List all available soundevents using specified stack name|
|snd_mergemethod|1||Sound merge method (0 == sum and clip, 1 == max, 2 == avg).|
|snd_mixahead|0.001|a||
|snd_mixer_master_dsp|1|cheat||
|snd_mixer_master_level|1|cheat||
|snd_musicvolume|0|a|Music volume|
|snd_mute_losefocus|false|a||
|snd_new_visualize|false|sv,cheat|Displays soundevent name played at it's 3d position|
|snd_occlusion_bounces|1|rep,cheat||
|snd_occlusion_debug|false|sv,cl,rep,cheat||
|snd_occlusion_min_wall_thickness|4|rep,cheat||
|snd_occlusion_rays|4|rep,cheat||
|snd_op_test_convar|720|cheat||
|snd_opvar_set_point_debug|false|sv,cl,rep,cheat||
|snd_opvar_set_point_update_interval|0.2|sv,cl,rep||
|snd_print_activetracks|cmd|cheat|List all active tracks|
|snd_print_arrangements|cmd|cheat|List all available sequence arrangments|
|snd_print_current_mixer_mixgroup|cmd||Get data related to mix group matching string|
|snd_print_samplers|cmd|cheat|List all available samplers|
|snd_print_sequences|cmd|cheat|List all available midi sequences|
|snd_rear_headphone_position|cmd||Specifies the position  (in degrees) of the virtual rear left/right headphones.|
|snd_rear_stereo_scale|1|rep,cheat||
|snd_rear_stereo_speaker_position|cmd||Specifies the position (in degrees) of the virtual rear left/right speakers.|
|snd_rear_surround_speaker_position|cmd||Specifies the position (in degrees) of the virtual rear left/right speakers.|
|snd_refdb|60|cheat|Reference dB at snd_refdist|
|snd_refdist|36|cheat|Reference distance for snd_refdb|
|snd_remove_all_soundevents|cmd|cheat|Remove all soundevents|
|snd_remove_soundevent|cmd|cheat|Remove the specified soundevent|
|snd_report_verbose_error|false|cheat|If set to 1, report more error found when playing sounds. |
|snd_samplers_play_note|cmd|cheat|Play a note from a specified sampler|
|snd_samplers_stop_note|cmd|cheat|Stop a note from a specified sampler|
|snd_sequence_set_track_bpm|cmd|cheat|Sets the tempo of the specified track|
|snd_sequence_set_track_transpose|cmd|cheat|Sets the transposition of the specified track|
|snd_sequence_stop_all_tracks|cmd|cheat|Stops all currently playing sequences|
|snd_sequence_stop_track|cmd|cheat|Stops the specified track|
|snd_sequencer_show_bpm|false|cheat||
|snd_sequencer_show_events|false|cheat||
|snd_sequencer_show_quantize_queue|false|cheat||
|snd_set_physics_surface_properties|cmd|cheat|Set physics surface properties for materials. Usage|
|snd_setmixer|cmd|cheat|Set named Mixgroup of current mixer to mix vol, mute, solo.|
|snd_setmixlayer|cmd|cheat|Set named Mixgroup of named mix layer to mix vol, mute, solo.|
|snd_showclassname|0|cheat||
|snd_showstart|0|cheat||
|snd_side_surround_speaker_position|cmd||Specifies the position (in degrees) of the virtual rear left/right speakers.|
|snd_sos_block_global_stack|false|cheat||
|snd_sos_block_stop_global_stack|true|cheat||
|snd_sos_calc_angle_debug|false|rep,cheat||
|snd_sos_cl_soundevent_pause_last|cmd|cl|Test|
|snd_sos_cl_soundevent_start|cmd|cl|Test|
|snd_sos_cl_soundevent_stop_last|cmd|cl|Test|
|snd_sos_cl_soundevent_unpause_last|cmd|cl|Test|
|snd_sos_debug_trigger_opvar|false|sv||
|snd_sos_default_update_stack|core_update_default|||
|snd_sos_flush_operators|cmd|cheat|Flush and re-parse the sound operator system|
|snd_sos_get_operator_field_info|cmd|cheat|Currently gets info for a single operator field|
|snd_sos_hide_simple_parameter_overwrite_warnings|true|||
|snd_sos_ingame_debug|false|cheat||
|snd_sos_list_operator_updates|false|cheat||
|snd_sos_max_event_base_depth|4|||
|snd_sos_opvar_debug|false|cheat||
|snd_sos_pause_soundevent|cmd|cheat|Pause the specified soundevent in the list|
|snd_sos_pause_system|false|cheat||
|snd_sos_print_class_sizes|cmd|cheat|Prints the sizes of relevant sos classes.|
|snd_sos_print_field_name_strings|cmd|cheat|Prints a list of currently cached field name strings|
|snd_sos_print_field_references|false|cheat||
|snd_sos_print_full_field_info|false|cheat||
|snd_sos_print_groups|cmd|cheat|Prints the current state of the groups system|
|snd_sos_print_operator_stack|cmd|cheat|Prints a master list of currently exposed variables|
|snd_sos_print_operator_stack_operator|cmd|cheat|Prints an operator from a stack|
|snd_sos_print_operator_stacks|cmd|cheat|Prints a list of currently available stacks|
|snd_sos_print_operators|cmd|cheat|Prints a list of currently available operators|
|snd_sos_print_stack_exec_list|cmd|cheat|Prints the current stack execution list|
|snd_sos_print_strings|cmd|cheat|Prints a list of currently cached strings|
|snd_sos_print_tool_properties|cmd|cheat|Prints the current state of tool properties.|
|snd_sos_report_entity_deleted|false|||
|snd_sos_resolve_execute_operator|cmd|cheat|Resolve the inputs and execute one specified operator from a specified stack|
|snd_sos_set_operator_field|cmd|cheat|Currently sets a single float operator field|
|snd_sos_set_operator_field_by_guid|cmd|cheat|Currently sets a single float operator field|
|snd_sos_show_block_debug|false|cheat|Spew data about the list of block entries.|
|snd_sos_show_entry_match_free|false|||
|snd_sos_show_mixgroup_path_errors|false|||
|snd_sos_show_operator_event_and_stack|true|cheat||
|snd_sos_show_operator_event_filter|0|cheat||
|snd_sos_show_operator_field_filter|0|cheat||
|snd_sos_show_operator_init|false|cheat||
|snd_sos_show_operator_not_executing|true|cheat||
|snd_sos_show_operator_operator_filter|0|cheat||
|snd_sos_show_operator_pause_entry|false|cheat||
|snd_sos_show_operator_shutdown|false|cheat||
|snd_sos_show_operator_stop_entry|false|cheat||
|snd_sos_show_operator_updates|false|cheat||
|snd_sos_show_opvar_updates|false|cheat||
|snd_sos_show_opvar_updates_filter|0|cheat||
|snd_sos_show_parameter_overwrite_warnings|false|||
|snd_sos_show_queuetotrack|false|cheat||
|snd_sos_show_soundevent_overwrites|false|||
|snd_sos_show_soundevent_param_overwrite|false|cheat||
|snd_sos_show_soundevent_start|false|cheat||
|snd_sos_show_track_list|false|||
|snd_sos_show_voice_elapsed_time|false|||
|snd_sos_soundevent_deferred_interval_time|0.1|||
|snd_sos_soundevent_filter|0|cheat||
|snd_sos_soundevent_max_deferred_time|5|||
|snd_sos_soundevent_profile|cmd|cheat|Dump a record of current soundevents and profile data|
|snd_sos_start_soundevent|cmd|cheat|Starts a specified soundevent|
|snd_sos_start_soundevent_at_pos|cmd|cheat|Starts a specified soundevent at the given position|
|snd_sos_stop_all_soundevents|cmd|cheat|Stops all soundevents currently on the execution list|
|snd_sos_stop_soundevent_guid|cmd|cheat|Stops a specified soundevent|
|snd_sos_stop_soundevent_index|cmd|cheat|Stops a specified soundevent|
|snd_sos_sv_soundevent_pause_last|cmd|sv|Test|
|snd_sos_sv_soundevent_start|cmd|sv|Test|
|snd_sos_sv_soundevent_stop_last|cmd|sv|Test|
|snd_sos_sv_soundevent_unpause_last|cmd|sv|Test|
|snd_sos_sv_test_gender|cmd|sv|Test|
|snd_sos_test_soundmessage|cmd|cheat|test|
|snd_sos_unpause_soundevent|cmd|cheat|UnPause the first soundevent in the list|
|snd_sos_use_case_sensitive_soundevents|false|||
|snd_sound_areas_debug|false|cl,rep,cheat||
|snd_sound_areas_debug_interval|0.2|cl,rep,cheat||
|snd_soundevent_clear_deferred|cmd|cheat|Clear the list of deferred soundevents for loading.|
|snd_soundmixer|Default_Mix|||
|snd_soundmixer_flush|cmd||Reload soundmixers.txt file.|
|snd_soundmixer_list_mix_groups|cmd||List all mix groups to dev console.|
|snd_soundmixer_list_mix_layers|cmd||List all mix layers to dev console.|
|snd_soundmixer_list_mixers|cmd||List all mixers to dev console.|
|snd_soundmixer_set_trigger_factor|cmd|cheat|Set named mix layer / mix group, trigger amount.|
|snd_soundmixer_setmixlayer_amount|cmd|cheat|Set named mix layer mix amount.|
|snd_soundmixer_version|2|||
|snd_spatialize_lerp|0|a,release||
|snd_steamaudio_display_probes|cmd||Load all the probes from a file and display probes based on the passed on arguments.|
|snd_steamaudio_dynamicpathing_max_samples|16|sv,cl,rep||
|snd_steamaudio_enable_reverb|0|release|Enable Steam Audio Reverb processor.|
|snd_steamaudio_export_scene|cmd|cheat|Exports scene currently used by Steam Audio as a phononscene file.|
|snd_steamaudio_pathing_caching_threshold|5|sv,cl,rep||
|snd_steamaudio_pathing_enable_caching|true|sv,cl,rep||
|snd_steamaudio_reverb_level_db|-3|release|Adjust overall volume (dB) of the output from Steam Audio Reverb processor.|
|snd_steamaudio_source_pathing_debug|false|a|Enable path visualization for steam_audio_source operator.|
|snd_steamaudio_source_pathing_debug_duration|0.01||Duration for which path remains visible. Should be close to update rate of the sound operator stack.|
|snd_steamaudio_source_pathing_enable_validation|false||Enable real-time pathing validation against dynamic geometry.|
|snd_stereo_speaker_pan_exponent|cmd||Specifies the exponent for the pan xfade from speaker to speaker if the 'exp' pan law is being used.|
|snd_stereo_speaker_pan_radial_weight|cmd||Apply cos(angle) * weight before pan law|
|snd_surround_speaker_pan_exponent|cmd||Specifies the exponent for the pan xfade from speaker to speaker if the 'exp' pan law is being used.|
|snd_surround_speaker_pan_radial_weight|cmd||Apply cos(angle) * weight before pan law|
|snd_toolvolume|1|a|Volume of sounds in tools (e.g. Hammer, SFM)|
|snd_use_baked_occlusion|0|rep,cheat,release||
|snd_vmidi_flush|cmd|cheat|Purge and reload all vmidi data and files.|
|snd_vmix_override_mix_decay_time|-1|cheat|If set > 0, overrides how long the decay time is on all mix graphs (in seconds). |
|snd_vmix_show_input_updates|false|cheat|If set to 1, show all incoming updates to vmix inputs. |
|snd_voipvolume|0.756374|a|Voice volume|
|sndplaydelay|cmd|||
|sos_debug_emit|false|sv,cl,rep||
|sound_device_override|Source2SDLDefaultDevice|a,release|ID of the sound device to use|
|soundinfo|cmd|release|Describe the current sound device with an active voice list.|
|soundlist|cmd||List all known sounds.|
|soundpatch_captionlength|2|sv,cl,rep|How long looping soundpatch captions should display for.|
|soundscape_debug|false|sv,cheat|When on, draws lines to all env_soundscape entities. Green lines show the active soundscape, red lines show soundscapes that aren't in range, and white lines show soundscapes that are in range, but not the active soundscape.|
|soundscape_dumpclient|cmd|cl,cheat|Dumps the client's soundscape data. |
|soundscape_fadetime|3|cl,cheat|Time to crossfade sound effects between soundscapes|
|soundscape_flush|cmd|sv|Flushes the server & client side soundscapes|
|soundscape_message|false|cl||
|soundscape_radius_debug|false|cl,cheat|Prints current volume of radius sounds|
|soundsystem_device_used|VoiceMeeterVAIO3Input(VB-AudioVoiceMeeterVAIO3)||Sound device in use (changing this does not change the soundsystem).|
|soundsystem_update_async|true|||
|soundsysteminfo|cmd||Describe the current sound device without an active voice list.|
|spawn_group_activate|cmd|sv,cheat|Activate specified spawngroup.|
|spawn_group_list|cmd|sv,cheat|List all spawn groups|
|spawn_group_load|cmd|sv,cheat|Load named spawn group.|
|spawn_group_unload|cmd|sv,cheat|Unload named spawn group.|
|spawngroup_ignore_timeouts|false|||
|speaker_config|0|a||
|spec_autodirector|true|cl,clientcmd_can_execute|Auto-director chooses best view modes while spectating|
|spec_centerchasecam|false|cl,a|Looks at the target player's center, instead of his eye position, in chase came mode|
|spec_chasedistance|96|cl|Chase cam's ideal distance from target|
|spec_chasedistancespeed|144|cl|Chase cam's ideal distance from target|
|spec_pos|cmd|cl,cheat|dump position and angles to the console|
|spec_replay_autostart|true|cl,a|Auto-start Killer Replay when available|
|spec_replay_bot|false|sv,release|Enable Spectator Hltv Replay when killed by bot|
|spec_replay_cache_ragdolls|true|cl|when set to 0, ragdolls will settle dynamically before and after Killer Replay|
|spec_replay_enable|0|rep,release|Enable Killer Replay, requires hltv server running (0|
|spec_replay_fadein|0.75|cl|Amount of time in seconds it takes to visually fade into replay, or into real-time after replay|
|spec_replay_fadeout|0.75|cl|Amount of time in seconds it takes to visually fade out of replay, or out of real-time before replay|
|spec_replay_fullframe|true||Send full frame on every hltv replay transition|
|spec_replay_leadup_time|5.3438|rep,release|Replay time in seconds before the highlighted event|
|spec_replay_message_time|9.5|rep,release|How long to show the message about Killer Replay after death. The best setting is a bit shorter than spec_replay_autostart_delay + spec_replay_leadup_time + spec_replay_winddown_time|
|spec_replay_on_death|false|rep,release|When > 0, sets the mode whereas players see delayed replay, and are segregated into a domain of chat and voice separate from the alive players|
|spec_replay_others_experimental|false|cl|Replay the last death of the round, if possible. Disabled on official servers by default. Experimental.|
|spec_replay_rate_base|1|rep,release|Base time scale of Killer Replay.Experimental.|
|spec_replay_rate_limit|3|rep,release|Minimum allowable pause between replay requests in seconds|
|spec_replay_rate_slowdown|1|cl|The part of Killer Replay right before death is played at this rate|
|spec_replay_rate_slowdown_length|0.5|cl|The part of Killer Replay right before death is played at this rate|
|spec_replay_review_sound|true|cl|When set to non-0, a sound effect is played during Killer Replay|
|spec_replay_sound_fadein|0.05|cl|Amount of time in seconds it takes to fade in the audio before or after replay|
|spec_replay_sound_fadeout|0|cl|Amount of time in seconds it takes to fade out the audio before or after replay|
|spec_replay_victim_pov|false|cl|Killer Replay - replay from victim's point of view (1); the default is killer's (0). Experimental.|
|spec_replay_winddown_time|2|sv,release|The trailing time, in seconds, of replay past the event, including fade-out|
|spec_track|0|cl|Tracks an entity in spec mode|
|spew_fonts|cmd||Spew information about font manager fonts|
|splitscreen_mode|0|a||
|splitscreen_testreadconfigconflict|cmd|||
|srgb_to_xyz|cmd||sRGB to CIEXYZ conversion|
|ss_add|cmd||Adds a splitscreen user.|
|ss_remove|cmd||Removes a splitscreen user.|
|ss_voice_hearpartner|false||Route voice between splitscreen players on same system.|
|startdemos|cmd|release|Play demos in demo sequence.|
|startmovie|cmd|norecord|Start recording movie frames.|
|stash_grab_all|cmd|cl|grab all items from the stash|
|stat_dropdown|cmd|cl|Select a category in the spectator stats dropdown|
|stat_dropdown_cycle|cmd|cl|Cycle through the stat dropdown categories in a specified direction (-1 = back, 1 = forward)|
|stat_dropdown_sort|cmd|cl|Cycle through the stat dropdown sort methods|
|stats|cmd||Prints server performance variables|
|stats_collect_gpu|false||While doing stats_display, collect GPU perf counters. Used for stats_print_gpu.|
|stats_display|0||Displays perf statistics information|
|stats_highlight_interval|10|cl|Interval between hightlight screens in the transition stats panel|
|stats_print|cmd||Prints out perf statistics to the console, clears perf history|
|stats_print_gpu|cmd||Prints out GPU perf statistics to the console.  Requires stats_display > 0, and stats_collect_gpu = true.  Optional argument of CSV filename|
|status|cmd|release|Print connection status|
|status_json|cmd|release|Print status in JSON format|
|steamlearn_data_submit_enable|false|sv|Whether we should be submitting data to SteamLearn|
|steamlearn_inference_http|false|sv|If we should use HTTP for inference queries|
|steamlearn_max_in_flight|100|sv|Maximum number of steamlearn requests that we can have in flight at once|
|steamlearn_request_timeout_s|5|sv|Timeout in seconds for backend requests|
|steamlearn_spew_um_times|true|sv|If we should spew how long inferences take to complete|
|sticker_opening_particle_emission_min|0.3|cl||
|sticker_opening_particle_emissionB_min|0|cl||
|sticker_opening_particle_velocity_min|0.1|cl||
|stickerbook_other_user_cache_time_s|1800|cl|Numer of seconds to cache other users' stickerbooks|
|stickerbook_self_cache_time_s|7200|cl|Numer of seconds to cache other users' stickerbooks|
|stop|cmd|release|Finish recording demo.|
|stopdemos|cmd|release|Stop looping demos (current demo will complete).|
|stopsound|cmd|cheat||
|stopsoundscape|cmd|cl,cheat|Stops all soundscape processing and fades current looping sounds|
|subclass_change|cmd|sv,cheat,vconsole_fuzzy|Changes the subclass of the given entity.  Arguments|
|subclass_create|cmd|sv,cheat,vconsole_fuzzy|Creates an entity of the given subclass where the player is looking.|
|surfaceprop|cmd|sv,cheat|Reports the surface properties at the cursor|
|sv_accelerate|10|sv,cl,nf,rep,release||
|sv_airaccelerate|10|sv,cl,nf,rep,release||
|sv_allchat|true|sv,nf,release|Players can receive all other players' text chat, no death restrictions|
|sv_alltalk|false|sv,nf,release|Players can hear all other players' voice communication, no team restrictions|
|sv_alternateticks|false|sp,release|If set, server only simulates entities on even numbered ticks. |
|sv_anim_queue_changes|true|sv||
|sv_autosave|true|sv,rep|Set to 1 to autosave game on level transition. Does not affect autosave triggers.|
|sv_banid_dev_enabled|false|||
|sv_banid_enabled|true|release|Whether server supports banid command|
|sv_bounce|0|sv,cl,nf,rep,release|Bounce multiplier for when physically simulated objects collide with other objects.|
|sv_cheats|true|nf,rep,release|Allow cheats on server|
|sv_client_max_interp_ratio|5|sv,cl,rep|This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected). If sv_client_min_interp_ratio is -1, then this cvar has no effect.|
|sv_client_min_interp_ratio|-1|sv,cl,rep|This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected).               -1 = let clients set cl_interp_ratio to anything  any other value = set minimum value for cl_interp_ratio|
|sv_client_predict|-1|sv,cl,rep|This can be used to force the value of cl_predict for connected clients (only while they are connected).    -1 = let clients set cl_predict to anything     0 = force cl_predict to 0     1 = force cl_predict to 1|
|sv_clientrates|cmd||Show client rates.|
|sv_clockcorrection_msecs|60|sv,release|The server tries to keep each player's m_nTickBase withing this many msecs of the server absolute tickcount|
|sv_cluster|0|release|Data center cluster this server lives in.|
|sv_debug_overlays_bandwidth|65536|release|Broadcast server debug overlays traffic|
|sv_debug_overlays_broadcast|false|nf,cheat,release|Broadcast server debug overlays|
|sv_dev_simulate_gcdown|cmd|sv|<state> Turn on/off simulated GC communications failure (GC is down in a way that we know it is down)|
|sv_disable_reliable_delta_retransmit|true||Assume that a reliable entity delta will be ack'ed and send future deltas relative to the last reliable delta.|
|sv_dota_auto_save_interval|300|sv||
|sv_dota_auto_save_min_players|10|sv|minimum number of players in the game to allow saves|
|sv_dota_auto_save_test_interval|120|sv||
|sv_dota_auto_save_test_interval_futz|30|sv||
|sv_dota_crash_sentinel_filename|0|sv|Filename of crash detection sentinel|
|sv_dota_custom_game_cache_download_stuck_mb|1|sv|We must download N megabytes within sv_dota_custom_game_cache_download_stuck_timeout seconds, or else we'll assume the download is stuck and give up|
|sv_dota_custom_game_cache_download_stuck_timeout|30|sv|Every N seconds, we must make download progress of at least sv_dota_custom_game_cache_download_stuck_mb megabytes, or else we'll assume the download is stuck and give up|
|sv_dota_custom_game_cache_download_timeout_total|300|sv|If we cannot finish downloading after N seconds, give up|
|sv_dota_custom_game_cache_lock_file_timeout|30|sv|If we cannot acquire lock on shared cache in N seconds, give up and fail UGC install|
|sv_dota_custom_game_cache_shared_folder|custom_game_cache|sv|Shared cache for downloaded custom game data.  (Dedicated server only)|
|sv_dota_custom_game_cache_test_download|cmd|sv|<custom game ID> [<expected_timestamp>].  Test code to cache UGC to dedicated server|
|sv_dota_dump_econ_item_stringtable|cmd|sv|sv_dota_dump_econ_item_stringtable|
|sv_dota_dump_modifier_stringtable|cmd|sv|sv_dota_dump_modifier_stringtable|
|sv_dota_league_auto_save_interval|30|sv||
|sv_dota_save_games|false|sv|Enable save game code|
|sv_dota_server_send_modifiers_using_buf_reliable|true|sv||
|sv_dota_speech_announcer_networking|true|sv,cheat|Set to 0 to prevent announcer speech from being matched on the client; match it on the server instead, like the old way.|
|sv_enable_alternate_baselines|1|release|Allow alternate baseline system, set to 2 for debugging spew.|
|sv_enable_delta_packing|true|release|When enabled, this allows for entity packing to use the property changes for building up the data. This is many times faster, but can be disabled for error checking.|
|sv_ent_showonlyhitbox|-1|sv,cheat||
|sv_ents_write_alarm|0|release|Print callstack every time CNetworkGameServerBase|
|sv_extra_client_connect_time|15||Seconds after client connect during which extra frames are buffered to prevent non-delta'd update|
|sv_filterban|1||Set packet filtering by IP mode|
|sv_friction|4|sv,cl,nf,rep,release|World friction.|
|sv_fullupdate|cmd||Force a full update for all clients.|
|sv_gameinstructor_disable|false|cl,rep,release|Force all clients to disable their game instructors.|
|sv_gameinstructor_enable|false|cl,rep,release|Force all clients to enable their game instructors.|
|sv_gravity|800|sv,cl,nf,rep,release|World gravity.|
|sv_hibernate_postgame_delay|5|release|# of seconds to wait after final client leaves before hibernating.|
|sv_hibernate_when_empty|true|release|Puts the server into extremely low CPU usage mode when no clients connected|
|sv_hitbox_debug|false|sv||
|sv_infinite_ammo|0|sv,cl,rep,cheat,release|Player's active weapon will never run out of ammo|
|sv_lagcompensationforcerestore|true|sv,cheat|Don't test validity of a lag comp restore, just do it.|
|sv_lan|false|release|Server is a lan server ( no heartbeat, no authentication, no non-class C addresses )|
|sv_lightquery_debug|false|sv,cheat||
|sv_log_onefile|false|a|Log server information to only one file.|
|sv_logbans|false|a|Log server bans in the server logs.|
|sv_logblocks|false|release|If true when log when a query is blocked (can cause very large log files)|
|sv_logecho|true|a|Echo log information to the console.|
|sv_logfile|false|a|Log server information in the log file.|
|sv_logflush|false|a|Flush the log file to disk on each write (slow).|
|sv_logsdir|logs|a|Folder in the game directory where server logs will be stored.|
|sv_massreport|false|sv||
|sv_max_queries_sec|3|release|Maximum queries per second to respond to from a single IP address.|
|sv_max_queries_sec_global|60|release|Maximum queries per second to respond to from anywhere.|
|sv_max_queries_window|30|release|Window over which to average queries per second averages.|
|sv_max_unreliable_delta_size|4096||Maximum allowable entity delta size over unreliable delivery.|
|sv_maxclientframes|128|||
|sv_maxrate|0|rep,release|Max bandwidth rate allowed on server, 0 == unlimited|
|sv_maxreplay|0||Maximum replay time in seconds|
|sv_maxspeed|320|sv,cl,nf,rep,release||
|sv_maxunlag|1|sv,release|Maximum lag compensation in seconds|
|sv_maxupdaterate|60|sv,cl,rep,release|Maximum updates per second that the server will allow|
|sv_maxvelocity|3500|sv,cl,rep,release|Maximum speed any ballistically moving object is allowed to attain per axis.|
|sv_memlimit|0|cheat,release|If set, whenever a game ends, if the total memory used by the server is greater than this # of megabytes, the server will exit.|
|sv_merge_changes_after_tick_with_calcdelta|1|release|This fixes bugs where pure calcdelta is used due to recipient changing but it doesn't pick up a field change where the value was changed back to same value as the from snapshot even though the destination fields change list does note the change. Set to 2 to spew any changes merged in by this fix.|
|sv_metaduplication|cmd|cheat|Check serializer meta for duplication, add verbose to command for full spew|
|sv_minrate|80000|rep,release|Min bandwidth rate allowed on server, 0 == unlimited|
|sv_minupdaterate|10|sv,cl,rep,release|Minimum updates per second that the server will allow|
|sv_mover_maxslope|0.7|sv,cl,nf,rep|The maximum slope the player can overcome [-]|
|sv_mover_pogodampingratio|1|sv,cl,nf,rep|The capsule pogo stick damping ratio [-]|
|sv_mover_pogofrequency|10|sv,cl,nf,rep|The capsule pogo stick frequency [hz].|
|sv_networkvar_perfieldtracking|true|release|Track individual field offset changes, rather than a single dirty flag for the whole entity.|
|sv_networkvar_validate|false|release|Validate each StateChanged against known offsets.|
|sv_noclipaccelerate|5|sv,cl,a,nf,rep||
|sv_noclipduringpause|false|sv,cl,rep,cheat|If cheats are enabled, then you can noclip with the game paused (for doing screenshots, etc.).|
|sv_noclipfriction|4|sv,cl,a,nf,rep|Friction during noclip move.|
|sv_noclipspeed|1200|sv,cl,a,nf,rep||
|sv_packstats|cmd|release|Show entity packing stats, pass 'clear' as argument to reset counts.|
|sv_parallel_checktransmit|0|sv|Set to 1 to use threaded checkentities for transmit/pvs on listen servers, 2 for dedicated servers.|
|sv_parallel_packentities|2|release|Set to 1 to use threaded snapshot sending on listen servers, 2 for dedicated servers.|
|sv_parallel_sendsnapshot|2|release|0|
|sv_password|0|prot,nf,norecord,release|Server password for entry into multiplayer games|
|sv_pausable|0|release|Is the server pausable.|
|sv_pause_on_console_open|false|a|1 = Pause the game when pressing ~ to open the console. CTRL+~ opens the console without pause.|
|sv_phys_animated_hierarchy|true|sv||
|sv_phys_debug_callback_entities|false|sv,cheat|Print all entities that get touch callbacks. Each entity is printed only once.|
|sv_phys_enabled|true|sv,cheat|Enable all physics simulation|
|sv_phys_sleep_enable|true|sv,cheat|Enable sleeping for dynamic physics bodies.|
|sv_phys_stop_at_collision|0|sv,cheat||
|sv_phys_visualize_awake|false|sv||
|sv_player_search_range|64|sv,cl,rep||
|sv_pure|cmd|release|Show user data.|
|sv_pure_kick_clients|true|release|If set to 1, the server will kick clients with mismatching files. Otherwise, it will issue a warning to the client.|
|sv_pure_trace|0|release|If set to 1, the server will print a message whenever a client is verifying a CRC for a file.|
|sv_pvs_entity|-1|sv|If set, only allows this ent index to network (other than players and things that force sending).|
|sv_pvs_max_distance|0|rep,release|if set, adds a maximum range to PVS/PAS checks|
|sv_pvs_random|false|sv|If set, objects blink in/out of pvs randomly.|
|sv_querycache_stats|cmd|sv|Display status of the query cache (client only)|
|sv_ragdoll_lru_debug|false|sv,rep,cheat||
|sv_rcon_banpenalty|0||Number of minutes to ban users who fail rcon authentication|
|sv_rcon_log|true||Enable/disable rcon logging.|
|sv_rcon_maxfailures|10||Max number of times a user can fail rcon authentication before being banned|
|sv_rcon_minfailures|5||Number of times a user can fail rcon authentication in sv_rcon_minfailuretime before being banned|
|sv_rcon_minfailuretime|30||Number of seconds to track failed rcon authentications|
|sv_regeneration_force_on|false|sv,cheat|Cheat to test regenerative health systems|
|sv_regeneration_wait_time|1|sv,rep||
|sv_region|-1|release|The region of the world to report this server in.|
|sv_remapper_loopsoundfix|false|sv,cl,rep||
|sv_remapper_range_multiplier|1|sv,cl,rep||
|sv_replaysdir|replays||Directory to store replays in|
|sv_reserve_slots_for_reconnecting_players_kick_prior|true||Kick a previously connected player with the same steamID if a replacement comes along|
|sv_script_think_interval|0.1|sv,cl,rep||
|sv_search_key|0|release||
|sv_sequence_debug|-1|sv||
|sv_sequence_debug2|-1|sv||
|sv_sequence_debug_verbose|true|sv||
|sv_sequence_model_substring|0|sv||
|sv_shared_team_pvs|true|sv|PVS is shared between teams|
|sv_showlagcompensation|0|sv,cl,rep,cheat|If > 0, show lag compensated hitboxes whenever a player is lag compensated. Value is for how long.|
|sv_showtags|cmd||Describe current gametags.|
|sv_shutdown|cmd|release|Sets the server to shutdown when all games have completed|
|sv_shutdown_immediately_on_request|false||The server will always shutdown on receiving the shutdown request, even if not hibernating|
|sv_skel_constraints_enable|false|rep,cheat||
|sv_skyname|sky_urb01|sv,cl,a,rep|Current name of the skybox texture|
|sv_snapshot_unlimited|false|rep,release|For debugging, don't throw away old snapshots so that if you break in debugger (on remote client or server) it won't require an uncompressed update to resume.  You may run out of memory of course...|
|sv_soundscape_printdebuginfo|cmd|sv,cheat|print soundscapes|
|sv_specaccelerate|5|sv,cl,a,nf,rep||
|sv_specnoclip|true|sv,cl,a,nf,rep||
|sv_specspeed|1200|sv,cl,a,nf,rep||
|sv_spewmeta|cmd|cheat|Spew serializer meta|
|sv_stats|true||Collect CPU usage stats|
|sv_steamgroup|0|nf,release|The ID of the steam group that this server belongs to. You can find your group's ID on the admin profile page in the steam community.|
|sv_steamgroup_exclusive|false|release|If set, only members of Steam group will be able to join the server when it's empty, public people will be able to join the server only if it has players.|
|sv_stopspeed|100|sv,cl,nf,rep,release|Minimum stopping speed when on ground.|
|sv_stressbots|false|release|If set to 1, the server calculates data and fills packets to bots. Used for perf testing.|
|sv_strict_notarget|false|sv|If set, notarget will cause entities to never think they are in the pvs|
|sv_tags|0|nf,release|Server tags. Used to provide extra information to clients when they're browsing for servers. Separate tags with a comma.|
|sv_temp_baseline_string_table_buffer_size|524288||Buffer size for writing string table baselines|
|sv_timeout|20||After this many seconds without a message from fully connected client, the client is dropped|
|sv_timeout_when_fully_connected|15|sv|Once fully connected, player will be kicked if he doesn't send a network message within this interval.|
|sv_timeout_when_fully_connected_customgame|30|sv|Once fully connected in a custom game game, player will be kicked if they don't send a network message within this interval.|
|sv_timeout_when_fully_connected_event|60|sv|Once fully connected in an event game, player will be kicked if they don't send a network message within this interval.|
|sv_timeout_when_fully_connected_tournament|5|sv|Once fully connected in a tournament game, player will be kicked if he doesn't send a network message within this interval.|
|sv_unify_random_seed|false|sv,cl,rep|Should we securely share seeds between the client and server?|
|sv_unlockedchapters|1|a|Highest unlocked game chapter.|
|sv_usenetworkvars|true||Use networkvar system.|
|sv_usercmd_custom_random_seed|false|sv,cl,rep,release|When enabled server will populate an additional random seed independent of the client|
|sv_usercmd_queue_spew_threshold|10|sv,release|Spew warning if command queue has grown above this many backlogged commands.|
|sv_visiblemaxplayers|-1|release|Overrides the max players reported to prospective clients|
|sv_voicecodec|vaudio_speex|release|Specifies which voice codec DLL to use in a game. Set to the name of the DLL without the extension.|
|sv_voiceenable|true|a,nf,release||
|sv_watchtransmit|-2|sv,release|Watch NetworkStateChanged info for this entity index.|
|sv_wateraccelerate|10|sv,cl,nf,rep,release||
|sv_waterfriction|1|sv,cl,nf,rep,release||
|sys_info|cmd|release|Print system information to the console|
|sys_minidumpexpandedspew|true|||
|sys_minidumpspewlines|2000|release|Lines of crash dump console spew to keep.|
|target_scan_use_query_cache|true|sv||
|telemetry_message|cmd|sv,cheat|Place a message in the telemetry timeline|
|telemetry_toggle_timespan|cmd|sv,cheat|Starts/stops a timespan with an ever increasing name.|
|test_arcana_initial_info|true|cl,a||
|Test_Checkpoint|cmd||Indicate to a test script that a checkpoint has been reached|
|test_compendium_endgame_stats|cmd|sv|test_compendium_endgame_stats|
|test_compendium_stats|cmd|sv|test_compendium_stats|
|test_dispatcheffect|cmd|sv,cheat|Test a clientside dispatch effect.  Usage|
|test_entity_blocker|cmd|sv,cheat|Test command that drops an entity blocker out in front of the player.|
|Test_ExitProcess|cmd|cheat|Test_ExitProcess <exit code> - immediately kill the process.|
|test_gameend|cmd|cl||
|test_list_entities|cmd|sv,cheat|test-list entities|
|Test_Loop|cmd||Test_Loop <loop name> - loop back to the specified loop start point unconditionally.|
|Test_LoopCount|cmd||Test_LoopCount <loop name> <count> - loop back to the specified loop start point the specified # of times.|
|Test_LoopForNumSeconds|cmd||Test_LoopForNumSeconds <loop name> <time> - loop back to the specified start point for the specified # of seconds.|
|test_prediction_results|cmd|cl||
|Test_RandomChance|cmd||Test_RandomChance <percent chance, 0-100> <token1> <token2...> - Roll the dice and maybe run the command following the percentage chance.|
|test_restoreonnewmodel|0|sv,cl,rep||
|Test_StartLoop|cmd||Test_StartLoop <loop name> - Denote the start of a loop. Really just defines a named point you can jump to.|
|Test_StartScript|cmd||Start a test script running..|
|testscript_debug|false||Debug test scripts.|
|tf_server_client_connect_timeout_s|8|sv||
|tf_server_client_read_timeout_s|4|sv||
|tf_server_client_write_timeout_s|4|sv||
|tf_server_handshake_enabled|false|sv||
|tf_server_idle_timeout_s|600|sv||
|tf_server_num_servers|1|sv||
|tf_server_read_timeout_s|1|sv||
|tf_server_stats_spew_interval_s|60|sv||
|tf_server_stats_spew_local|false|sv||
|tf_server_write_timeout_s|1|sv||
|think_limit|10|sv,cl,rep,release|Maximum think time in milliseconds, warning is printed if this is exceeded.|
|thirdperson|cmd|cl,cheat,execute_per_tick|Switch to thirdperson camera.|
|thirdperson_mayamode|cmd|cl,cheat|Switch to thirdperson Maya-like camera controls.|
|thirdpersonshoulder|cmd|cl|Switch to thirdperson-shoulder camera.|
|ti11_show_frontpage_winner|false|cl||
|ti11_takeover_force_bilibili|false|cl||
|ti11_takeover_force_stream|false|cl||
|ti11_takeover_force_youtube|false|cl||
|ti11_takeover_spoilers_blocked|false|cl,a,per_user|Avoid spoilers for takeover matches|
|ti11_takeover_time_override|0|cl||
|ti11_upcoming_events_time_override|0|cl||
|ti12_live_video_spoilers_blocked|true|cl,a,per_user|Avoid spoilers for frontpage matches|
|tier_treasure_mockup_item_offset_y|200|cl||
|tier_treasure_mockup_tier_offset_x|-200|cl||
|tier_treasure_mockup_tier_offset_z|100|cl||
|timedemo|cmd|release|Play a demo and report performance info.|
|timedemo_end|-1||Ends timedemo on given tick.|
|timedemo_start|-1||Starts timedemo on given tick.|
|timedemoquit|cmd|release|Play a demo, report performance info, and then exit|
|toggle|cmd|norecord,release|Toggles specified convar value on and off.|
|toggleconsole|cmd|norecord,release|Show/hide the console.|
|toggleshoppanel|cmd|cl|toggles shop|
|toolhud_enable|true|||
|tools_renderscenes|true|||
|top_bar_message|cmd|cl|test top bar status message. usage|
|treasure_escalating_rares_popup_seen|true|cl,a,per_user||
|treasure_opening_particle_emission_max|2|cl||
|treasure_opening_particle_emission_min|0.3|cl||
|treasure_opening_particle_emissionB_max|1|cl||
|treasure_opening_particle_emissionB_min|0|cl||
|treasure_opening_particle_velocity_max|2|cl||
|treasure_opening_particle_velocity_min|0.1|cl||
|treasure_peek_details|cmd|cl|Displays details about the peek status of the currently open treasure|
|truesight_force_ended|false|cl||
|truesight_force_live|false|cl||
|tutorial_cleanup_post|cmd|sv||
|tutorial_experience_closed|cmd|sv||
|tutorial_speech_end|cmd|sv||
|tutorial_start_lesson|cmd|sv|Jump to the passed tutorial lesson|
|tutorial_testui|cmd|sv||
|tutorial_tip_dismissed|cmd|sv||
|tv_advertise_watchable|false|prot,nf,norecord,release|GOTV advertises the match as watchable via game UI, clients watching via UI will not need to type password|
|tv_allow_autorecording_index|-1|sv,release|When >=0 restricts autorecording only to the specified TV index|
|tv_allow_camera_man|true|sv|Auto director allows spectators to become camera man|
|tv_allow_static_shots|true|sv,release|Auto director uses fixed level cameras for shots|
|tv_autorecord|false|release|Automatically records all games as SourceTV demos.|
|tv_autoretry|true|release|Relay proxies retry connection after network timeout|
|tv_broadcast|false|release|Automatically broadcasts all games as GOTV demos through Steam.|
|tv_broadcast1|false|release|Automatically broadcasts all games as GOTV[1] demos through Steam.|
|tv_broadcast_keyframe_interval|3|release|The frequency, in seconds, of sending keyframes and delta fragments to the broadcast relay server|
|tv_broadcast_keyframe_interval1|3|release|The frequency, in seconds, of sending keyframes and delta fragments to the broadcast1 relay server|
|tv_broadcast_max_requests|20|release|Max number of broadcast http requests in flight. If there is a network issue, the requests may start piling up, degrading server performance. If more than the specified number of requests are in flight, the new requests are dropped.|
|tv_broadcast_max_requests1|20|release|Max number of broadcast1 http requests in flight. If there is a network issue, the requests may start piling up, degrading server performance. If more than the specified number of requests are in flight, the new requests are dropped.|
|tv_broadcast_resend|cmd||resend broadcast data to broadcast relay|
|tv_broadcast_startup_resend_interval|10|release|The interval, in seconds, of re-sending startup data to the broadcast relay server (useful in case relay crashes, restarts or startup data http request fails)|
|tv_broadcast_status|cmd|release|Print out broadcast status|
|tv_broadcast_url|http|//localhost|080 |
|tv_broadcast_url1|http|//localhost|080 |
|tv_chatgroupsize|0|release|Set the default chat group size|
|tv_chattimelimit|0.2|release|Limits spectators to chat only every n seconds|
|tv_clients|cmd|release|Shows list of connected SourceTV clients.|
|tv_debug|0|release|SourceTV debug info.|
|tv_delay|120|sv,release|SourceTV broadcast delay in seconds|
|tv_deltacache|2|release|Enable delta entity bit stream cache|
|tv_demo_starttick|0|||
|tv_dispatchmode|1|release|Dispatch clients to relay proxies|
|tv_dota_auto_record|false|sv|If enabled, a demo will automatically be recorded for every game|
|tv_dota_auto_record_stressbots|false|sv|If enabled, a demo will automatically be recorded for stressbot games|
|tv_enable|false|nf,release|Activates SourceTV on server.|
|tv_enable1|false|nf,release|Activates SourceTV[1] on server.|
|tv_enable_delta_frames|true|release|Indicates whether or not the tv should use delta frames for storage of intermediate frames. This takes more CPU but significantly less memory.|
|tv_enable_dynamic|false|nf,release|When enabled, changes in tv_enable convars cause immediate startup or shutdown of hltv server|
|tv_extended_logging|false|||
|tv_grouprelaydatareliable|false||When enabled, this will collect all information for relay sending into a single datagram to ensure that the data stays together through a potentially large number of relays|
|tv_grouprelaydataunreliable|false||When enabled, this will collect all information for relay sending into a single datagram to ensure that the data stays together through a potentially large number of relays|
|tv_grouprelaydatavoice|false||Similar to tv_grouprelaydata, but controls whether or not the voice channels should be routed into the grouped data for the relays|
|tv_instant_replay_full_frame|true||Send embedded full frames|
|tv_instant_replay_full_frame_build_threaded|false||Build the full frames on a seperate job thread|
|tv_instant_replay_full_frame_time|30||Seconds between full frame embeddeds|
|tv_listen_voice_indices|0|cl,user|Bitfield of playerslots to listen to voice messages from when connected to SourceTV, default is none|
|tv_listen_voice_indices_h|0|cl,user|High 32 bits of bitfield of playerslots to listen to voice messages from when connected to SourceTV, default is none|
|tv_log_director_events|false|sv|Log game events being considered by the director|
|tv_maxclients|128|release|Maximum client number on SourceTV server.|
|tv_maxclients_relayreserved|0|release|This number of relay client connections are reserved for SourceTV relays.|
|tv_maxrate|0|release|Max SourceTV spectator bandwidth rate allowed, 0 == unlimited|
|tv_mem|cmd|release|hltv memory statistics. Use with 'ent 10' (dump entity 10 memory usage) or 'top 8' (dump top 8 memory users) or 'class' CWorld (dump CWorld class)|
|tv_msg|cmd|sv|Send a screen message to all clients.|
|tv_name|SourceTV|release|SourceTV host name|
|tv_nochat|false|a,user|Don't receive chat messages from other SourceTV spectators|
|tv_overridemaster|false|release|Overrides the SourceTV master root address.|
|tv_password|0|prot,nf,norecord,release|SourceTV password for all clients|
|tv_playcast_delay_prediction|true|release||
|tv_playcast_delay_resync|0|release|To alleviate intermittent network connectivity problems, this is the number of seconds to wait before actually re-syncing the stream after failure|
|tv_playcast_retry_timeout|12|release|In case of intermittent network problems, how long should playcast retry fragment retrieval before resorting to resync|
|tv_port|27020|release|Host SourceTV[0] port|
|tv_port1|27021|release|Host SourceTV[1] port|
|tv_rate_multiplier|2||Multiply requested rate by this value to adjust Dota TV send rate|
|tv_record|cmd|release|Starts SourceTV demo recording.|
|tv_record_immediate|1|release|tv_record starting the moment tv_record was executed, not tv_delay earlier|
|tv_relay|cmd|release|Connect to SourceTV server and relay broadcast.|
|tv_relay_hard_shutdown|false|||
|tv_relay_quit_after_game|true||Quit after a game has been relayed, do not hibernate|
|tv_relay_rate|500000||default rate for relays|
|tv_relay_secret_code|true||When enabled, this will use a uniquely generated server code to authenticate relay to relay connections. This code is coordinated via the GC or some external means rather than by clients directly|
|tv_relaypassword|0|prot,nf,norecord,release|SourceTV password for relay proxies|
|tv_relayvoice|true|release|Relay voice data|
|tv_retry|cmd|release|Reconnects the SourceTV relay proxy.|
|tv_secret_code|true||When enabled, this will use a uniquely generated server code to authenticate relay connections. This code is coordinated via the GC or some external means rather than by clients directly|
|tv_show_allchat|true|sv,release||
|tv_snapshotrate|20|rep,release|Snapshots broadcast per second|
|tv_snapshotrate1|32|release|Snapshots broadcast per second, GOTV[1]|
|tv_status|cmd|release|Show SourceTV server status.|
|tv_stop|cmd|release|Stops the SourceTV broadcast.|
|tv_stoprecord|cmd|release|Stops SourceTV demo recording.|
|tv_threaded_merge_entity_deltas|true||Enable SourceTV threading of delta merging|
|tv_timeout|20|release|SourceTV connection timeout in seconds.|
|tv_title|SourceTV|release|Set title for SourceTV spectator UI|
|tv_transmitall|false|rep,release|Transmit all entities (not only director view)|
|tv_update_hibernation_enabled|true||Allow SourceTV to control server hibernation state.|
|tv_window_size|16||Specifies the number of seconds worth of frames that the tv replay system should keep in memory. Increasing this greatly increases the amount of memory consumed by the TV system|
|ugc_fake_state|-1|cl|1=s, 2=L, 4=I, 8=U, 16=D, 32=P|
|ui_hud_dist|24|cl,rep|distance from the player to the hud|
|unbind|cmd|release|Unbind a key.|
|unbindall|cmd|release|Unbind all keys.|
|unloadTool|cmd||unload the specified tool|
|unpause|cmd|release|Clear the pause state of the server.|
|unsubscribe_all_game_modes|cmd|cl|Unsubscribes from all custom games. They will be uninstalled by the Steam client when you close Dota 2.|
|unsubscribe_custom_game|cmd|cl|Stops subscribing to a specific custom game. It will be uninstalled when you exit Dota 2.|
|url_execute|cmd|cl|Executes url-based commands, used for incoming commands from url-based launches when the game's already running.|
|use_item_client|cmd|cl,norecord,clientcmd_can_execute|Use the item in the indicated slot. <hero name> <slot name>|
|users|cmd||Show user info for players on server.|
|vcon_clear_buffered_log|cmd|norecord|Clear buffered logging|
|vcon_clients|cmd|norecord|List connections|
|vconsole_rcon_server_details|0|norecord,release,server_cant_query|when non-empty allows for easy vconsole connection to the dedicated server.|
|viewmodel_fov|54|cl,cheat||
|violence_ablood|true|a|Draw alien blood|
|violence_agibs|true|a|Show alien gib entities|
|violence_hblood|true|a|Draw human blood|
|violence_hgibs|true|a|Show human gib entities|
|vis_debug_currentcluster|cmd||Show the current cluster number|
|vis_debug_drawcluster|cmd||Add cluster # to visualization, (-1) to clear|
|vis_debug_dumpvisibleclusters|cmd||Show the list of visible clusters|
|vis_debug_find_los|cmd||Find or clear the vis LOS to here|
|vis_debug_lock|cmd||Lock vis LOS origin to current|
|vis_debug_record_start|cmd||Record a path to debug vis|
|vis_debug_record_stop|cmd||Record a path to debug vis|
|vis_debug_show|cmd||Show/hide the vis debug visualization|
|vis_debug_sunclusters|cmd||Showing clusters for sun/csm rendering. Red (full sun csm & lighting), Orange (no viewmodel sun or csm), Green (no sun at all)|
|vis_debug_tracelos|cmd||Trace rays and check vis from the current camera|
|vis_enable|true||Enable precomputed visibility when true|
|vis_force|false|sv,cheat||
|vismon_poll_frequency|0.5|sv,cheat||
|vismon_trace_limit|12|sv,cheat||
|vmem_dump|cmd||Dump memory stats to log.|
|vmix_debug_list|cmd||Debug dump the list of available vmix graphs|
|vmix_input|cmd|cheat|Set an input mix value|
|vmix_output|cmd|cheat|Dump main graph control output values|
|voice_all_icons|false|cl|Draw all players' voice icons|
|voice_always_sample_mic|true|a|For systems experiencing a hang/stall when using voice chat.|
|voice_chat_bubble_show_volume|true|cl,a|Visualize the volume transmitted with the icon displaying speech.|
|voice_chat_bubbles|true|cl,a|Whether to draw chat bubbles int the UI or not|
|voice_clientdebug|0|cl||
|voice_debugfeedbackfrom|false|||
|voice_fadeouttime|0.005|||
|voice_initial_buffer_ms|200|||
|voice_loopback|false|user||
|voice_min_buffer_ms|100|||
|voice_modenable|true|cl,a,release,clientcmd_can_execute|Enable/disable voice in this mod.|
|voice_player_speaking_delay_threshold|0.5|sv,cheat||
|voice_sequence_maximum_wait_time|0.5||When receiving packets out of sequence, wait this many seconds for missing sequences to arrive|
|voice_serverdebug|false|sv||
|voice_stall_ms|250|||
|voice_threshold|0|cl,a||
|voice_threshold_delay|0.5|||
|voice_vox|0|cl,a,per_user|Voice chat uses a vox-style always on|
|voice_vox_current_peak|0|cl|Current peak value (out of 64k) of the incoming voice stream|
|volume|1|a|Sound volume|
|volume_fog_clipmap_update|1|cheat||
|volume_fog_clipmaps_enabled|false|cheat||
|volume_fog_depth|128|||
|volume_fog_disable|false|cheat||
|volume_fog_dither_scale|3|cheat||
|volume_fog_enable_jitter|true|cheat||
|volume_fog_enable_stereo|true|cheat||
|volume_fog_enlarge_frusta|2|cheat||
|volume_fog_height|160|||
|volume_fog_intermediate_textures_hdr|false|||
|volume_fog_jitter_offset_random|true|||
|volume_fog_show_volumes|false|cheat||
|volume_fog_width|240|||
|vphys2_friction_factor|1|cheat|Change global friction factor|
|vphys2_restitution_factor|1|cheat|Change global restitution factor|
|vphysics_force_apply_magnitude|1|||
|vphysics_return_implicit_velocity|false|||
|vprof_counters|0|||
|vprof_counters_show_minmax|false|||
|vprof_dump_counters|cmd||Dump vprof counters to the console|
|vprof_generate_report|cmd||Generate a report to the console.|
|vprof_generate_report_budget|cmd||Generate a report to the console based on budget group.|
|vprof_generate_report_hierarchy|cmd||Generate a report to the console.|
|vprof_off|cmd||Disable vprof|
|vprof_on|cmd||Enable vprof|
|vprof_remote_start|cmd||Request a VProf data stream from the remote server (requires authentication)|
|vprof_remote_stop|cmd||Stop an existing remote VProf data request|
|vprof_reset|cmd||Reset the stats in VProf profiler|
|vprof_reset_peaks|cmd||Reset just the peak time in VProf profiler|
|vprof_scope_entity_clientthink|false|cl|Set to 1 to generate individual VPROF nodes for each client entity's think function.|
|vprof_scope_entity_gamephys|false|sv||
|vprof_scope_entity_thinks|false|sv,cl,rep||
|vprof_think_limit|false|sv||
|vprof_vtrace|cmd||Toggle whether vprof data is sent to VTrace|
|vtune|cmd||Controls VTune's sampling.|
|watch_server|cmd|cl|Watch a server steam id|
|winter2022_gameplay_tip_number|0|cl,a||
|winter2022_show_game_info|true|cl,a||
|workshop_download_debug|0|cl|Test different custom game download states|
|world_dump_loaded_worlds|cmd||Dump all of the worlds that we know about|
|world_layer_list|cmd||List all world layers|
|world_layer_set_visible|cmd||Show or hide the specified world layer|
|writeid|cmd||Writes a list of permanently-banned user IDs to file.|
|writeip|cmd||Save the ban list to file.|
|writekeybindings|cmd|release|Saves current key bindings to disk.|
|zoom_sensitivity_ratio|1|cl,a,per_user|Additional mouse sensitivity scale factor applied when FOV is zoomed in.|
