# Video script — Sensors in an IoT System

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Sensors** are devices that measure a property of the world — temperature, light, movement, pressure, moisture — and turn it into data. In IoT architecture they form the **perception layer**, the bottom layer that touches the physical world. A sensor's reading is the system's first fact; every later decision stands on it, which is why Jordan's book places sensors before networks: bad sensing cannot be repaired by good transmitting.
Between the sensors and the wider network stands the **gateway**: it collects readings from many nearby sensors, may do first processing on them, translates between the sensors' short-range protocols and the internet's, and passes the data onward. The gateway is also a guard post — the point where local traffic is checked before it leaves. One gateway can serve a room, a greenhouse or a street of lamps.
