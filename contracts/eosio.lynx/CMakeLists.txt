add_contract(eosio.lynx eosio.lynx ${CMAKE_CURRENT_SOURCE_DIR}/src/eosio.lynx.cpp)

target_include_directories(eosio.lynx
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/include)

set_target_properties(eosio.lynx
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")
