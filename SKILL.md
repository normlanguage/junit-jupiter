# junit.jupiter Skill

Use this skill to work with Norm module `junit.jupiter` version 7. Use only declarations listed below.

## `junit.jupiter`

Source: `AfterAll.norm`

### `AfterAll`

```norm
annotation AfterAll implements TypeTarget, FunctionTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `AfterEach.norm`

### `AfterEach`

```norm
annotation AfterEach implements TypeTarget, FunctionTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `Assertions.norm`

### `Assertions`

```norm
class Assertions
```

#### `Assertions`

```norm
Assertions(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Double arg0, Double arg1)
```

Parameters:

- `arg0`: `Double`
- `arg1`: `Double`

Returns: `Void`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Void`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Integer arg0, Integer arg1, String? arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `String?`

Returns: `Void`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Long arg0, Long arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Long`

Returns: `Void`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Void`

### `assertionsAssertEquals`

```norm
Void assertionsAssertEquals(Any? arg0, Any? arg1, String? arg2)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`
- `arg2`: `String?`

Returns: `Void`

### `assertionsAssertFalse`

```norm
Void assertionsAssertFalse(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

### `assertionsAssertFalse`

```norm
Void assertionsAssertFalse(Boolean arg0, String? arg1)
```

Parameters:

- `arg0`: `Boolean`
- `arg1`: `String?`

Returns: `Void`

### `assertionsAssertNotEquals`

```norm
Void assertionsAssertNotEquals(Double arg0, Double arg1)
```

Parameters:

- `arg0`: `Double`
- `arg1`: `Double`

Returns: `Void`

### `assertionsAssertNotEquals`

```norm
Void assertionsAssertNotEquals(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Void`

### `assertionsAssertNotEquals`

```norm
Void assertionsAssertNotEquals(Long arg0, Long arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Long`

Returns: `Void`

### `assertionsAssertNotEquals`

```norm
Void assertionsAssertNotEquals(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Void`

### `assertionsAssertNotNull`

```norm
Void assertionsAssertNotNull(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Void`

### `assertionsAssertNotNull`

```norm
Void assertionsAssertNotNull(Any? arg0, String? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `String?`

Returns: `Void`

### `assertionsAssertNotSame`

```norm
Void assertionsAssertNotSame(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Void`

### `assertionsAssertNull`

```norm
Void assertionsAssertNull(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Void`

### `assertionsAssertNull`

```norm
Void assertionsAssertNull(Any? arg0, String? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `String?`

Returns: `Void`

### `assertionsAssertSame`

```norm
Void assertionsAssertSame(Any? arg0, Any? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Any?`

Returns: `Void`

### `assertionsAssertTrue`

```norm
Void assertionsAssertTrue(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

### `assertionsAssertTrue`

```norm
Void assertionsAssertTrue(Boolean arg0, String? arg1)
```

Parameters:

- `arg0`: `Boolean`
- `arg1`: `String?`

Returns: `Void`

## `junit.jupiter`

Source: `BeforeAll.norm`

### `BeforeAll`

```norm
annotation BeforeAll implements TypeTarget, FunctionTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `BeforeEach.norm`

### `BeforeEach`

```norm
annotation BeforeEach implements TypeTarget, FunctionTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `Disabled.norm`

### `Disabled`

```norm
annotation Disabled implements TypeTarget, FunctionTarget, RuntimeRetention
```

#### `value`

```norm
String value
```

Type: `String`

#### `Disabled`

```norm
Disabled(String? value)
```

Parameters:

- `value`: `String?`

## `junit.jupiter`

Source: `DisplayName.norm`

### `DisplayName`

```norm
annotation DisplayName implements TypeTarget, FunctionTarget, RuntimeRetention
```

#### `value`

```norm
String value
```

Type: `String`

## `junit.jupiter`

Source: `Nested.norm`

### `Nested`

```norm
annotation Nested implements TypeTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `RepeatedTest.norm`

### `RepeatedTest`

```norm
annotation RepeatedTest implements TypeTarget, FunctionTarget, RuntimeRetention
```

#### `failureThreshold`

```norm
Integer failureThreshold
```

Type: `Integer`

#### `name`

```norm
String name
```

Type: `String`

#### `value`

```norm
Integer value
```

Type: `Integer`

#### `RepeatedTest`

```norm
RepeatedTest(Integer? failureThreshold, String? name, Integer value)
```

Parameters:

- `failureThreshold`: `Integer?`
- `name`: `String?`
- `value`: `Integer`

## `junit.jupiter`

Source: `Tag.norm`

### `Tag`

```norm
annotation Tag implements TypeTarget, FunctionTarget, RuntimeRetention, InheritedAnnotation, RepeatableAnnotation
```

#### `value`

```norm
String value
```

Type: `String`

## `junit.jupiter`

Source: `Test.norm`

### `Test`

```norm
annotation Test implements TypeTarget, FunctionTarget, RuntimeRetention
```

## `junit.jupiter`

Source: `TestInstance.norm`

### `TestInstance`

```norm
annotation TestInstance implements TypeTarget, RuntimeRetention, InheritedAnnotation
```

#### `value`

```norm
Lifecycle value
```

Type: `Lifecycle`

## `junit.jupiter.TestInstance`

Source: `TestInstance/Lifecycle.norm`

### `Lifecycle`

```norm
enum Lifecycle
```

#### `PER_CLASS`

```norm
PER_CLASS
```

#### `PER_METHOD`

```norm
PER_METHOD
```

