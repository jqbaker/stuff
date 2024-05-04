# stuff

UE_LOG(LogTemp, Warning, TEXT("stuff"));

if (GEngine)

GEngine->AddOnScreenDebugMessage(-1, 2.0f, FColor::Yellow, FString::Printf(TEXT("stuff")));

FInputActionKeyMapping Left("Left", EKeys::Left, 0, 0, 0, 0);

PlayerInput->AddActionMapping(Left);

InputComponent->BindAction("Left", IE_Pressed, this, &AYour_PC::Left);
