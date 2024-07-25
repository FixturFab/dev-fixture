# FixturFab Dev Test Fixture 

The Dev Test Fixture is an open source [bed-of-nails test fixture](https://en.wikipedia.org/wiki/Bed_of_nails_tester) to aid in firmware and manufacturing test development, and early stage manufacturing test. 

![Dev](https://shop.fixturfab.com/web/image/product.product/7474/image_1024/%5B206-0016-00%5D%20Dev%20Test%20Fixture%20Base?unique=921932a)

Dev Test Fixtures are available for sale on the [FixturFab Website](https://shop.fixturfab.com) in either a [Kit](https://shop.fixturfab.com/shop/210-0001-00-dev-test-fixture-kit-8764) or [Assembled](https://shop.fixturfab.com/shop/206-0016-00-dev-test-fixture-base-8431?category=3&search=dev) form. If you build or buy one, please help the project by documenting bugs with a GitHub issue. 

The Dev Test Fixture is designed to be a low-cost, easy to use fixture to help get someone started with low volume PCBA functional testing. Additional information on how to design and develop PCBA functional tests can be found at the [FixturFab Blog](https://fixturfab.com/articles/). 

## Dev Test Fixture Specifications

| Specification                  | Value                       |
|--------------------------------|-----------------------------|
| Max Board Size                 | 196mm x 180mm (7.7in x 7in) |
| Maximum Test Points            | 100                         |
| Service Life                   | 1K+ Units                   |
| Exchangeable Cartridge Support | No                          |
| Top Probing Support            | No                          |  
| Side Probing Support           | No                          |
| Weight                         | 1.4kg (3lbs)                |
| Materials                      | Acrylic & MDF               |

## Assembly and Release Files

Exported source (STLs, Assemblies, PDFs) can be found attached to the [latest release](google.com).

The latest working version of the Assembly can also be [viewed here](https://a360.co/3L6yBcP). 

## Compatible Probes, Receptacles, and Other Components

The Dev Test Fixture series is designed to utilize low-cost, readily available test probes and receptacles. Here is a list of recommended components: 

### Test Probes and Receptacles

Generic Probes and Receptacles with "2" (2.5mm) or "3" (5mm) collar heights are supported. Match the Probe and Receptacle pitches, (i.e P50 probes in R50 receptacles).

Receptacle part numbers take the following form: 

`R{pitch size}-{collar height}{termination style}`

Probe part numbers take the following form: 

`P{pitch size}-{tip style}{tip diameter}`

Pitch Sizes: 
- 100: 100mil/2.54mm minimum center to center spacing
- 75: 75mil/1.9mm minimum center to center spacing
- 50: 50mil/1.27mm minimum center to center spacing

Collar Heights: 
- 2: 2.5mm collar 
- 3: 5mm collat

Termination Styles:
- C: Crimp
- S: Solder Cup
- W: Wire Wrap

Tip Style: 
- A: Cup
- B: Needle
- LM: Spear
- Q: Waffle

Tip Diameter: 
- Varies widely, refer to the datasheet/documentation for the specific probe you are purchasing. 

These components can be sourced from sourced from Aliexpress, Amazon, or [FixturFab](https://shop.fixturfab.com). 


## Guide Pins

Locating the device under test can be done in many different ways, some methods are: 

- Spring Loaded Guide Pins
  - GP-2U - Umbrella Head
  - GP-2T - Threaded Head (M3 threads)
  - GP-2S - Spear Head
  - These components can be sourced from sourced from Aliexpress, Amazon, or [FixturFab](https://shop.fixturfab.com). 
- Dowel Pins 
  - Standard sizes can be found on Amazon or McMaster
- Cradle
  - Custom designed 3D printed or machine cradle
  - Attaches to the probe plate and aligns the DUT with the test probes


### Pressure Pins

Use a 45mm Pressure Pin (also referred to as POM). These can be 3D Printed, or sourced from Aliexpress, Amazon, or [FixturFab](https://shop.fixturfab.com).


## Contributing

If you would like to contribuute to the project, awesome! Check out the [contributing page]() to get started. 