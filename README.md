# stuff

UE_LOG(LogTemp, Warning, TEXT("stuff"));

if (GEngine)
GEngine->AddOnScreenDebugMessage(-1, 2.0f, FColor::Yellow, FString::Printf(TEXT("stuff")));
