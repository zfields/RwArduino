add_executable(BlinkWithoutDelay BlinkWithoutDelay.cpp)
target_link_libraries(BlinkWithoutDelay LINK_PUBLIC remote_wiring firmata serial_wiring pthread)
add_dependencies(BlinkWithoutDelay remote_wiring firmata serial_wiring)

add_executable(Button Button.cpp)
target_link_libraries(Button LINK_PUBLIC remote_wiring firmata serial_wiring pthread)
add_dependencies(Button remote_wiring firmata serial_wiring)

add_executable(Debounce Debounce.cpp)
target_link_libraries(Debounce LINK_PUBLIC remote_wiring firmata serial_wiring pthread)
add_dependencies(Debounce remote_wiring firmata serial_wiring)

add_executable(DigitalInputPullup DigitalInputPullup.cpp)
target_link_libraries(DigitalInputPullup LINK_PUBLIC remote_wiring firmata serial_wiring pthread)
add_dependencies(DigitalInputPullup remote_wiring firmata serial_wiring)

add_executable(StateChangeDetection StateChangeDetection.cpp)
target_link_libraries(StateChangeDetection LINK_PUBLIC remote_wiring firmata serial_wiring pthread)
add_dependencies(StateChangeDetection remote_wiring firmata serial_wiring)
