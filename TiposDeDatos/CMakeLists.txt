cmake_minimum_required(VERSION 3.30)
project(TiposDeDatos)

set(CMAKE_CXX_STANDARD 20)

add_executable(TiposDeDatos main.cpp)
add_executable(conversionTipos conversionTipos.cpp)
add_executable(conversionExplicita conversionExplícita.cpp)
add_executable(usoDeConstantes usoDeConstantes.cpp)
add_executable(verificaPrimeraLetra verificaPrimeraLetra.cpp)
add_executable(verificarPositivo verificarPositvo.cpp)
add_executable(verificaAprobado verificaAprobado.cpp)
add_executable(verificaCandidato verificaCandidato.cpp)
