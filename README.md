Akka.Serialization.MessagePack
===
[![Build status](https://ci.appveyor.com/api/projects/status/9uvd8ilxkg8dqxn3/branch/master?svg=true)](https://ci.appveyor.com/project/ravengerUA/akka-serialization-messagepack/branch/master)

Akka.NET serialization with [MessagePack](https://github.com/neuecc/MessagePack-CSharp)

## It supports
- Primitive types (`int`, `string`, `long`, etc)
- Build-in types (`DateTime`, `DateTimeOffset`, `TimeSpan`, `Guid`, `Uri`, `Enum`, etc)
- Collections (`List<T>`, `HashSet<T>`, `Dictionary<TKey, TValue>`, etc)
- Immutable Collections
- Exceptions (only on full .NET Framework)
- Akka.NET specific types (`ActorPath` and `ActorRef`)
- Object types (polymorphic serialization)
- Generic types
- Version tolerance (???)

## It does not support
- Internal and private classes
- Classes with private or internal constructors
- F# types (`Set`, `Map`, `List`, `FSharpAsync<T>`, discriminated unions)
- Handling circular references
- Preserve object references
- Exceptions (on NetCore)

## Maintainer
[alexvaluyskiy](https://github.com/alexvaluyskiy)
