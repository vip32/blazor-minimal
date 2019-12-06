# blazor-minimal

TODO:
- App.razor: dynamic component library loading 
  - instead of (App.Razor) ```AdditionalAssemblies="new[] { typeof(About).Assembly }```
  - https://github.com/aspnet/AspNetCore/issues/5465
  - planned for net5 https://github.com/aspnet/AspNetCore/milestone/61 (Lazy loading of application areas)