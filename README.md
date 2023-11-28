# ZEST_CORE_STM32L496RG
ZEST_CORE_STM32L496RG custom target for Mbed OS.

## Usage
In your project root directory:

1.  Add the custom target to your project:

    ```shell
    mbed add https://github.com/catie-aq/mbed_zest-core-stm32l496rg.git zest-core-stm32l496rg
    ```

2. Enable the custom target by adding or overwriting the `custom_targets.json` at the
   root of the project:

    ```shell
    cp zest-core-stm32l496rg/custom_targets.json .
    ```

3. Compile for the custom target:

   ```shell
   mbed compile --target ZEST_CORE_STM32L496RG --toolchain GCC_ARM
   ```
