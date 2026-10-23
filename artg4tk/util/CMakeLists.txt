cet_make_library(SOURCE
  StringIDs.cc
  util.cc
  LIBRARIES
  PUBLIC
  Geant4::G4graphics_reps
  art::Framework_Core
  art::Framework_Principal
  art::Framework_Services_Registry
  messagefacility::MF_MessageLogger
  Geant4::G4geometry	
  Geant4::G4graphics_reps
  PRIVATE
  cetlib_except::cetlib_except
)

install_headers()
install_source()
