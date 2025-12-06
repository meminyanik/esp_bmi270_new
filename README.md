# esp_bmi270_new
This is the working version of the BMI270 on ESP32

## TODO
Create the `components` directory, then clone `espp` as a submodule within that directory e.g. `git submodule add https://github.com/esp-cpp/espp components/espp`, then make sure to run `git submodule update --init --recursive`.
   
Afterwards, simply update your `CMakeLists.txt` to add
    ```cmake
    # add the component directories that we want to use
    set(EXTRA_COMPONENT_DIRS
      "components/espp/components"
    )
    ```