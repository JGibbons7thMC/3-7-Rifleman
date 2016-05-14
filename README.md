# 3-7-Rifleman

comment "Exported from Arsenal by Sgt. J. Gibbons";

comment "Remove existing items";
removeAllWeapons this;
removeAllItems this;
removeAllAssignedItems this;
removeUniform this;
removeVest this;
removeBackpack this;
removeHeadgear this;
removeGoggles this;

comment "Add containers";
this forceAddUniform "rhs_uniform_FROG01_d";
for "_i" from 1 to 6 do {this addItemToUniform "ACE_fieldDressing";};
for "_i" from 1 to 6 do {this addItemToUniform "ACE_elasticBandage";};
for "_i" from 1 to 6 do {this addItemToUniform "ACE_quikclot";};
this addItemToUniform "ACE_EarPlugs";
for "_i" from 1 to 2 do {this addItemToUniform "ACE_morphine";};
this addItemToUniform "ItemcTabHCam";
this addItemToUniform "ACE_IR_Strobe_Item";
this addItemToUniform "ACE_Flashlight_MX991";
this addItemToUniform "ACE_MapTools";
for "_i" from 1 to 6 do {this addItemToUniform "ACE_packingBandage";};
for "_i" from 1 to 2 do {this addItemToUniform "ACE_tourniquet";};
this addVest "rhsusf_spc_rifleman";
this addItemToVest "ACE_microDAGR";
for "_i" from 1 to 2 do {this addItemToVest "rhsusf_mag_15Rnd_9x19_FMJ";};
for "_i" from 1 to 4 do {this addItemToVest "rhs_mag_an_m8hc";};
this addItemToVest "ACE_HandFlare_Green";
this addItemToVest "ACE_HandFlare_Red";
this addItemToVest "SmokeShellGreen";
this addItemToVest "SmokeShellRed";
for "_i" from 1 to 2 do {this addItemToVest "rhs_mag_m18_green";};
this addItemToVest "rhsusf_mag_15Rnd_9x19_JHP";
for "_i" from 1 to 10 do {this addItemToVest "rhs_mag_30Rnd_556x45_M855A1_Stanag";};
this addBackpack "rhsusf_assault_eagleaiii_coy";
for "_i" from 1 to 5 do {this addItemToBackpack "ACE_CableTie";};
this addItemToBackpack "rhsusf_ANPVS_15";
this addHeadgear "rhsusf_lwh_helmet_marpatd";
this addGoggles "rhs_googles_black";

comment "Add weapons";
this addWeapon "rhs_weap_m27iar";
this addPrimaryWeaponItem "rhsusf_acc_anpeq15";
this addPrimaryWeaponItem "rhsusf_acc_ACOG_USMC";
this addPrimaryWeaponItem "RH_TD_ACB_b";
this addWeapon "rhsusf_weap_m9";
this addWeapon "Binocular";

comment "Add items";
this linkItem "ItemMap";
this linkItem "ItemCompass";
this linkItem "ItemWatch";
this linkItem "tf_anprc152_1";
this linkItem "ItemAndroid";

comment "Set identity";
this setFace "WhiteHead_09";
this setSpeaker "Male12ENG";
