



|  | Issue | Recommendation |
| :---: | --- | --- |
| 1 | in the react-native-windows repo when a developer tries to reference a C# WinRT <br>component in their C++/WinRT app, they will propably hit a build error not being <br>able to find the C# WinRT XAML type info | add #include <winrt/Cam.Cam_XamlTypeInfo.h> in the cppwinrt PCH |
| 2 |  |  |

