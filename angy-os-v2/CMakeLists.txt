# CMakeList.txt: progetto CMake per angy-os-v2. Includere l'origine e definire
# qui la logica specifica del progetto.
#

# Aggiungere l'origine all'eseguibile di questo progetto.
add_executable (angy-os-v2 "angy-os-v2.cpp" "angy-os-v2.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET angy-os-v2 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Aggiungere i test e, se necessario, installare le destinazioni.
