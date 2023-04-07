#define GWORLD = 0xEF0F440
#define FNAME = 0xEF89F80
#define RESULT_DA = 17
#define GObject = 0xED79528

//Offsets
	uintptr_t UWorld = 0xEF0F440;
	uintptr_t ObjectID = 0x18;

	//UWorld
	uintptr_t OwningGameInstance = 0x1B8; //UGameInstance*
	uintptr_t Levels = 0x170; //TArray<ULevel*>
	uintptr_t GameState = 0x158; //AGameStateBase*
	uintptr_t PersistentLevel = 0x30; //ULevel*


	//UWorld -> PersistentLevel (ULevel)
	uintptr_t AActors = 0x98;
	uintptr_t ActorCount = 0xA0;

	//UGameInstance
	uintptr_t LocalPlayers = 0x38; //TArray<ULocalPlayer*>

	//UPlayer
	uintptr_t PlayerController = 0x30; //APlayerController*

	//APlayerController
	uintptr_t AcknowledgedPawn = 0x330; //APawn*
	uintptr_t PlayerCameraManager = 0x340; //APlayerCameraManager*


	//AActor
	uintptr_t bHidden = 0x58; //char
	uintptr_t RootComponent = 0x190; //USceneComponent*
	uintptr_t CustomTimeDilation = 0x64; //float

	//ACharacter
	uintptr_t Mesh = 0x310; //USkeletalMeshComponent*

	//APawn
	uintptr_t PlayerState = 0x2A8; //APlayerState*


	uintptr_t TeamIndex = 0x10B0; //AFortPlayerStateAthena
	uintptr_t ReviveFromDBNOTime = 0x44c0; //AFortPlayerStateAthena
	uintptr_t LocalActorPos = 0x128;
	uintptr_t CurrentWeapon = 0x8f8;
	uintptr_t BoneArray = 0x5f0;
