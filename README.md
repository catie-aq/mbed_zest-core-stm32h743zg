# Zest_Core_STM32H743ZI
[Zest_Core_STM32H743ZI](https://gitlab.com/catie_6tron/zest-core-stm32h743zi-hardware)
custom target for Mbed OS.

## Usage
In your project root directory:

1.  Add the custom target to your project:

    ```shell
    mbed add https://gitlab.com/catie_6tron/zest-core-stm32h743zi.git
    ```

2. Enable the custom target by adding or overwriting the `custom_targets.json` at the
   root of the project:

    ```shell
    cp zest-core-stm32h743zi/custom_targets.json .
    ```

3. Compile for the custom target:

   ```shell
   mbed compile --target ZEST_CORE_STM32H743ZI
   ```
