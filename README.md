# Fortnite-sigs
The latest fortnite sigs

Sigs:
UWorld = 48 8b 0d ? ? ? ? 48 85 c9 74 30 e8 ? ? ? ? 48 8b f8;UObjectArray = 48 89 05 ? ? ? ? E8 ? ? ? ? 40 84 F6;

GetNameIndex = 48 89 5C 24 18 55 56 57 48 8B EC 48 83 EC 30 8B 01 48 8B 

F1GetWeaponStats = 48 83 EC 58 48 8B 91 ? ? ? ? 48 85 D2 0F 84 ? ? ? ? F6 81 ? ? ? ? ? 74 10 48 8B 81 ? ? ? ? 48 85 C0 0F 85 ? ? ? ? 48 8B 8A ? ? ? ? 48 89 5C 24 ? 48 8D 9A ? ? ? ? 48 85 C9;

ProcessEvent = 40 55 56 57 41 54 41 55 41 56 41 57 48 81 EC ? ? ? ? 48 8D 6C 24 ? 48 89 9D ? ? ? ? 48 8B 05 ? ? ? ? 48 33 C5 48 89 85 ? ? ? ? 8B 41 0C 45 33 F6 3B 05 ? ? ? ? 4D 8B F8 48 8B F2 4C 8B E1 41 B8 ? ? ? ? 7D 2A;

CalculateShot = 48 89 5C 24 ? 4C 89 4C 24 ? 55 56 57 41 54 41 55 41 56 41 57 48 8D 6C 24 ? 48 81 EC ? ? ? ? 48 8B F9 4C 8D 6C 24 ?;

CalculateSpread = 83 79 78 ? 4C 8B C9 75 0F 0F 57 C0 C7 02 ? ? ? ? F3 41 0F 11 ? C3 48 8B 41 70 8B 48 04 89 0A 49 63 41 78 48 6B C8 1C 49 8B 41 70 F3 0F 10 44 01 ? F3 41 0F 11 ? C3;

CalculateSpreadCaller = 0F 57 D2 48 8D 4C 24 ? 41 0F 28 CD E8 ? ? ? ? 48 8B 4D B0 0F 28 F0 48 85 C9 74 05 E8 ? ? ? ? 48 8B 4D 98 48 8D 05 ? ? ? ? 48 89 44 24 ? 48 85 C9 74 05 E8 ? ? ? ? 48 8B 4D 88;

GetViewPoint = 48 89 5C 24 ? 48 89 74 24 ? 57 48 83 EC 20 48 8B D9 41 8B F0 48 8B 49 30 48 8B FA E8 ? ? ? ? BA ? ? ? ? 48 8B C8;

GObjects = 48 8B 0D ? ? ? ? 48 98 4C 8B 04 D1 48 8D 0C 40 49 8D 04 C8 EB ?;

GetObjectName = 40 53 48 83 EC 20 48 8B D9 48 85 D2 75 45 33 C0 48 89 01 48 89 41 08 8D 50 05 E8 ? ? ? ? 8B 53 08 8D 42 05 89 43 08 3B 43 0C 7E 08 48 8B CB E8 ? ? ? ? 48 8B 0B 48 8D 15 ? ? ? ? 41 B8 ? ? ? ? E8 ? ? ? ? 48 8B C3 48 83 C4 20 5B C3 48 8B 42 18;

Free = 48 85 C9 74 2E 53 48 83 EC 20 48 8B D9 48 8B 0D ? ? ? ? 48 85 C9 75 0C;

CalculateProjectionMatrixGivenView = 45 0F 57 C0 45 8B 81;

LineOfSightTo = 40 55 53 56 57 48 8D 6C 24 ? 48 81 EC ? ? ? ? 48 8B 05 ? ? ? ? 48 33 C4 48 89 45 E0 49;



Offset:
uWorld: 0x9864730
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
