# MycopunkModTemplate

## How to use:
- Use this as template for your repo
- Uncomment and change the path to `Assembly-CSharp.dll` in `.csproj`
- If you need more stuff like `Unity.TextMeshPro` or `UnityEngine.UI`, just add a reference to them the same way as main dll
- If you want `Unity.InputSystem`, add this line:
  - `<PackageReference Include="UnityEngine.Modules" Version="2022.3.5" IncludeAssets="compile" />`