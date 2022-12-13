Abrir o Android Studio =>  Click on AVD Manager =>  Wipe Data (Your Target Device )

https://stackoverflow.com/questions/57000915/error-adb-exited-with-exit-code-1-performing-streamed-install

#Limpando cache android studio pelo terminal linux

Pega o nome do avd:


bash$ ls -a $HOME/.android/avd/*.ini | cut -f1 -d.


bash$ emulator -avd Nexus_S_API_31 -wipe-data


## Ou execute o script limpa_emulador

bash$ sh limpa_emulador


