# faster crafting

client side mod that makes crafting faster for you.

simply install it with a mod manager or manually download and drop the dll into your bepinex/plugins folder.


```cs
[HarmonyPatch(typeof(InventoryGui), "UpdateRecipe")]
class fasterCrafting
{
    static void Prefix(ref InventoryGui __instance)
    {
        __instance.m_craftDuration = .25f;
    }
}
```