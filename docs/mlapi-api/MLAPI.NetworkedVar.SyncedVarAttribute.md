---  
id: MLAPI.NetworkedVar.SyncedVarAttribute  
title: MLAPI.NetworkedVar.SyncedVarAttribute  
---

<div class="markdown level0 summary">

SyncedVar attribute. Use this to automatically syncronize fields from
the server to clients.

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

<div class="level2">

System.Dynamic.ExpandoObject

</div>

</div>

<div classs="implements">

##### Implements

<div>

System.Runtime.InteropServices.\_Attribute

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

Attribute.Equals(Object)

</div>

<div>

Attribute.GetCustomAttribute(Assembly, Type)

</div>

<div>

Attribute.GetCustomAttribute(Assembly, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttribute(MemberInfo, Type)

</div>

<div>

Attribute.GetCustomAttribute(MemberInfo, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttribute(Module, Type)

</div>

<div>

Attribute.GetCustomAttribute(Module, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttribute(ParameterInfo, Type)

</div>

<div>

Attribute.GetCustomAttribute(ParameterInfo, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(Assembly)

</div>

<div>

Attribute.GetCustomAttributes(Assembly, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(Assembly, Type)

</div>

<div>

Attribute.GetCustomAttributes(Assembly, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(MemberInfo)

</div>

<div>

Attribute.GetCustomAttributes(MemberInfo, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(MemberInfo, Type)

</div>

<div>

Attribute.GetCustomAttributes(MemberInfo, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(Module)

</div>

<div>

Attribute.GetCustomAttributes(Module, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(Module, Type)

</div>

<div>

Attribute.GetCustomAttributes(Module, Type, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(ParameterInfo)

</div>

<div>

Attribute.GetCustomAttributes(ParameterInfo, Boolean)

</div>

<div>

Attribute.GetCustomAttributes(ParameterInfo, Type)

</div>

<div>

Attribute.GetCustomAttributes(ParameterInfo, Type, Boolean)

</div>

<div>

Attribute.GetHashCode()

</div>

<div>

Attribute.IsDefaultAttribute()

</div>

<div>

Attribute.IsDefined(Assembly, Type)

</div>

<div>

Attribute.IsDefined(Assembly, Type, Boolean)

</div>

<div>

Attribute.IsDefined(MemberInfo, Type)

</div>

<div>

Attribute.IsDefined(MemberInfo, Type, Boolean)

</div>

<div>

Attribute.IsDefined(Module, Type)

</div>

<div>

Attribute.IsDefined(Module, Type, Boolean)

</div>

<div>

Attribute.IsDefined(ParameterInfo, Type)

</div>

<div>

Attribute.IsDefined(ParameterInfo, Type, Boolean)

</div>

<div>

Attribute.Match(Object)

</div>

<div>

Attribute.\_Attribute.GetIDsOfNames(Guid, IntPtr, UInt32, UInt32,
IntPtr)

</div>

<div>

Attribute.\_Attribute.GetTypeInfo(UInt32, UInt32, IntPtr)

</div>

<div>

Attribute.\_Attribute.GetTypeInfoCount(UInt32)

</div>

<div>

Attribute.\_Attribute.Invoke(UInt32, Guid, UInt32, Int16, IntPtr,
IntPtr, IntPtr, IntPtr)

</div>

<div>

Attribute.TypeId

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

    [AttributeUsage(AttributeTargets.Field, Inherited = true, AllowMultiple = false)]
    public class SyncedVarAttribute : Attribute, _Attribute

## Fields

### Channel

<div class="markdown level1 summary">

The channel to send changes on.

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public string Channel

#### Field Value

| Type          | Description |
|---------------|-------------|
| System.String |             |

### SendTickrate

<div class="markdown level1 summary">

The maximum times per second this var will be synced. A value of 0 will
cause the variable to sync as soon as possible after being changed. A
value of less than 0 will cause the variable to sync only at once at
spawn and not update again.

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public float SendTickrate

#### Field Value

| Type          | Description |
|---------------|-------------|
| System.Single |             |

### Implements

<div>

System.Runtime.InteropServices.\_Attribute

</div>