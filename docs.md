# time

Time and date helpers: now, sleep, format, parse, monotonic.

This document is auto-generated from the function signatures in this repository. 
It lists every public function the library exposes.

## Install

```sh
nox pull time
```

## Import

```novus
import lib/time time;
```

## Functions

### `elapsed_ms`

```novus
fn elapsed_ms(start_ns: i64, end_ns: i64) -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `elapsed_us`

```novus
fn elapsed_us(start_ns: i64, end_ns: i64) -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `format_duration_ms`

```novus
fn format_duration_ms(ms: i64) -> str;
```
_Defined in: `darwin_arm64.nov`_

### `get_time_ms`

```novus
fn get_time_ms() -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `get_time_s`

```novus
fn get_time_s() -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `get_time_us`

```novus
fn get_time_us() -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `sleep_ms`

```novus
fn sleep_ms(ms: i32) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `sleep_s`

```novus
fn sleep_s(seconds: i32) -> void;
```
_Defined in: `darwin_arm64.nov`_

### `timer_elapsed_ms`

```novus
fn timer_elapsed_ms(start: i64) -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `timer_elapsed_s`

```novus
fn timer_elapsed_s(start: i64) -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `timer_elapsed_us`

```novus
fn timer_elapsed_us(start: i64) -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `timer_start`

```novus
fn timer_start() -> i64;
```
_Defined in: `darwin_arm64.nov`_

### `to_u8_time`

```novus
fn to_u8_time(v: i32) -> i32;
```
_Defined in: `linux_arm64.nov`_
