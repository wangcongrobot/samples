set(ProjectName Sample-01-Motion)
project(${ProjectName})
set(Project_SRC Sample.cpp)
add_executable(${ProjectName} ${Project_SRC}) 
target_link_libraries(${ProjectName} ${DUO_LIBRARY}) 
