# LaunchWrapper

LaunchWrapper is a fork of https://github.com/Enaium/LaunchWrapper (which is a fork of Mojang's LegacyLauncher: https://github.com/Mojang/LegacyLauncher)
  
It provides classloading functionality allowing mixins to be applied to Minecraft's bytecode. This enables runtime modification of Minecraft's code
without having to patch the source code, making it easier to redistribute open source mods (though ARR mods can also benefit from this)

LaunchWrapper is required for DracoLoader to properly function, without it, the mod loader will not work.