Sigs:
Uworld: 48 8B 05 ? ? ? ? 4D 8B C2
GoObject: 48 8B 05 ? ? ? ? 48 8B 0C C8 48 8B 04 D1
FnFree: 48 85 C9 0F 84 ? ? ? ? 53 48 83 EC 20 48 89 7C 24 30 48 8B D9 48 8B 3D ? ? ? ? 48 85 FF 0F 84 ? ? ? ? 48 8B 07 4C 8B 40 30 48 8D 05 ? ? ? ? 4C 3B C0
ProjectWorldToScreen: E8 ? ? ? ? 41 88 07 48 83 C4 30
GetBoneMatrix: E8 ? ? ? ? 48 8B 47 30 F3 0F 10 45
LineOfSightTo: E8 ? ? ? ? 48 8B 0D ? ? ? ? 33 D2 40 8A F8
CalculateShot: 48 89 5C 24 ? 4C 89 4C 24 ? 55 56 57 41 54 41 55 41 56 41 57 48 8D 6C 24 ? 48 81 EC ? ? ? ? 48 8B F9 4C 8D 6C 24 ?
CalculateSpreadHook = E8 ? ? ? ? 48 8D 4B 28 E8 ? ? ? ? 48 8B C8
SpreadCaller = 0F 57 D2 48 8D 4C 24 ? 41 0F 28 CC E8 ? ? ? ? 48 8B 4D B0 0F 28 F0 48 85 C9
GetNameByIndex = 48 89 5C 24 ? 48 89 74 24 ? 55 57 41 56 48 8D AC 24 ? ? ? ? 48 81 EC ? ? ? ? 48 8B 05 ? ? ? ? 48 33 C4 48 89 85 ? ? ? ? 45 33 F6 48 8B F2 44 39 71 04 0F 85 ? ? ? ? 8B 19 0F B7 FB E8 ? ? ? ? 8B CB 48 8D 54 24

Offsets:
uWorld: 0x9864730
LineOfSightTo: 0xcf43ba5
FortniteFree: 0x995c3bc
GObjects: 0x968b288
GNames: 0x48c302f5
Engine::World::Levels: 0x138
Engine::World::PersistentLevel: 0x30
Engine::GameInstance::LocalPlayers: 0x38
Engine::World::OwningGameInstance: 0x180
Engine::Controller::ControlRotation: 0x288
Engine::PlayerController::PlayerCameraManager: 0x2B8
Engine::PlayerController::ClientReturnToMainMenuWithTextReason: 0x0
Engine::PlayerController::AcknowledgedPawn: 0x2A0
Engine::Pawn::PlayerState: 0x240
Engine::Actor::RootComponent: 0x130
Engine::Character::Mesh: 0x280
Engine::SceneComponent::RelativeLocation: 0x11C
Engine::SceneComponent::ComponentVelocity: 0x140
Engine::StaticMeshComponent::StaticMesh: 0x480
Engine::SkinnedMeshComponent::CachedWorldSpaceBounds: 0x618
Engine::Actor::CustomTimeDilation: 0x98
FortniteGame::Offsets::FortniteGame::FortWeapon::LastFireTimeVerified: 0x9C0
FortniteGame::Offsets::FortniteGame::FortWeapon::LastFireTime: 0x9BC
FortniteGame::FortPawn::bIsDBNO: 0x57E
FortniteGame::FortPawn::bIsDying: 0x540
FortniteGame::FortPawn::bSpotted: 0x542
FortniteGame::FortPlayerStateAthena::TeamIndex: 0xED0
FortniteGame::FortPlayerStateAthena::SquadId: 0x1054
FortniteGame::FortPickup::PrimaryPickupItemEntry: 0x2A8
FortniteGame::FortItemDefinition::DisplayName: 0x88
FortniteGame::FortItemDefinition::Tier: 0x6C
FortniteGame::FortItemEntry::ItemDefinition: 0x18
FortniteGame::FortPawn::CurrentWeapon: 0x600
FortniteGame::FortWeapon::WeaponData: 0x378
FortniteGame::FortWeapon::LastFireAbilityTime: 0xC08
FortniteGame::FortWeaponItemDefinition::WeaponStatHandle: 0x820
FortniteGame::FortProjectileAthena::FireStartLoc: 0x880
FortniteGame::FortBaseWeaponStats::ReloadTime: 0x10C
FortniteGame::FortBaseWeaponStats::ReloadScale: 0x110
FortniteGame::FortBaseWeaponStats::ChargeDownTime: 0x13C
FortniteGame::FortRangedWeaponStats::RecoilHoriz: 0x210
FortniteGame::FortRangedWeaponStats::RecoilVert: 0x200
FortniteGame::FortRangedWeaponStats::RecoilDownsightsMultiplier: 0x22C
FortniteGame::FortRangedWeaponStats::Spread: 0x16C
