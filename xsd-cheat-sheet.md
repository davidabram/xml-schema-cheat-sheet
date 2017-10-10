<?xml version="1.0" standalone="no"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 20010904//EN"
 "http://www.w3.org/TR/2001/REC-SVG-20010904/DTD/svg10.dtd">
<svg version="1.0" xmlns="http://www.w3.org/2000/svg"
 width="100" height="100" viewBox="0 0 626.000000 626.000000"
 preserveAspectRatio="xMidYMid meet">
<g transform="translate(0.000000,626.000000) scale(0.100000,-0.100000)"
fill="#000000" stroke="none">
<path d="M1015 6241 c-56 -25 -102 -67 -128 -115 l-22 -41 -3 -1032 -2 -1033
-93 0 c-177 0 -272 -44 -354 -165 -54 -78 -53 -62 -53 -1094 0 -1042 -1 -1010
58 -1106 65 -105 164 -153 333 -162 l108 -6 3 -656 c3 -655 3 -656 25 -697 26
-48 72 -90 128 -115 38 -18 128 -19 2115 -19 1987 0 2077 1 2115 19 56 25 102
67 128 115 22 41 22 42 25 697 l3 656 108 6 c169 9 268 57 333 162 59 96 58
64 58 1100 0 1024 0 1023 -52 1099 -84 122 -177 166 -355 166 l-93 0 0 375 c0
301 -3 382 -14 410 -8 18 -63 89 -123 157 -158 180 -442 505 -484 552 -20 23
-118 136 -219 251 -101 116 -211 242 -245 280 -34 39 -82 93 -106 121 -24 28
-58 61 -75 72 l-30 22 -1525 0 c-1453 0 -1526 -1 -1564 -19z m2935 -872 c0
-572 2 -644 16 -668 34 -58 12 -56 624 -61 l565 -5 3 -307 2 -308 -2030 0
-2030 0 0 995 0 995 1425 0 1425 0 0 -641z m-2628 -1886 c44 -93 102 -217 130
-278 27 -60 53 -113 57 -117 4 -5 31 52 61 125 29 72 74 177 100 232 26 55 58
124 71 153 l24 52 213 0 213 0 -32 -57 c-18 -32 -41 -70 -51 -85 -10 -14 -18
-29 -18 -32 0 -3 -26 -49 -59 -103 -47 -80 -162 -279 -283 -492 l-20 -35 23
-40 c12 -23 48 -84 79 -136 31 -52 68 -115 82 -140 39 -68 97 -169 193 -335
101 -173 105 -180 105 -187 0 -5 -96 -8 -212 -8 l-213 0 -144 290 c-78 160
-146 292 -150 295 -4 2 -21 -28 -37 -67 -16 -39 -75 -170 -130 -292 l-101
-221 -212 -3 c-116 -1 -211 0 -211 2 0 9 204 370 345 611 29 50 69 120 90 158
l37 67 -48 83 c-26 45 -58 100 -70 122 -12 22 -59 105 -104 185 -171 302 -230
408 -230 414 0 3 95 6 211 6 l210 0 81 -167z m1685 87 c12 -41 37 -129 56
-195 20 -66 49 -165 65 -220 31 -108 98 -380 133 -537 12 -54 25 -95 30 -92 5
3 9 13 9 22 0 9 12 60 26 112 14 52 39 145 55 205 49 184 139 478 216 708 l26
77 244 0 c188 0 243 -3 243 -12 1 -26 20 -369 30 -531 5 -92 19 -342 30 -555
11 -213 23 -424 27 -469 l6 -83 -181 0 -181 0 -5 33 c-9 51 -27 560 -33 930
-3 186 -9 334 -13 330 -4 -4 -24 -71 -45 -148 -20 -77 -45 -167 -55 -200 -29
-92 -114 -366 -155 -500 -20 -66 -44 -145 -54 -175 -11 -30 -31 -97 -46 -147
l-28 -93 -143 0 c-166 0 -149 -12 -187 130 -14 52 -51 187 -82 300 -102 371
-195 756 -195 811 0 14 -4 19 -9 14 -5 -6 -14 -125 -20 -265 -30 -734 -42
-996 -46 -1007 -3 -10 -47 -13 -175 -13 -170 0 -170 0 -170 23 0 12 5 81 10
152 6 72 19 276 30 455 11 179 24 388 30 465 5 77 14 228 20 335 6 107 13 201
15 208 4 10 59 12 252 10 l248 -3 22 -75z m1853 -585 l0 -665 313 -1 c171 -1
319 -2 327 -3 13 -1 15 -25 15 -156 l0 -155 -515 0 -515 0 -3 810 c-1 446 0
816 3 823 3 9 51 12 190 12 l185 0 0 -665z m298 -2082 l-3 -588 -2025 0 -2025
0 -3 588 -2 587 2030 0 2030 0 -2 -587z"/>
</g>
</svg>


## Jednostavna XML Schema
~~~~
<?xml version="1.0"?>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema" targetNamespace="http://interoperabilnost.hr" xmlns="http://interoperabilnost.hr" elementFormDefault="qualified">
  <xs:element name="note">
    <xs:complexType>
      <xs:sequence>
	<xs:element name="to" type="xs:string"/>
	<xs:element name="from" type="xs:string"/>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema> 
~~~~

<br />

## Simple Types

  - xs:string
  - xs:decimal
  - xs:integer
  - xs:boolean
  - xs:date
  - xs:time

~~~~
<xs:element name="start_date" type="xs:date"/>
~~~~

<br />

## XML Facets

  - xs:minInclusive 
  - xs:maxInclusive
  - xs:minExclusive
  - xs:maxExclusive
  - xs:enumeration
  - xs:pattern
  - xs:whiteSpace
  - xs:length
  - xs:minLength
  - xs:maxLength
  - xs:totalDigits
  - xs:fractionDigits

### Min-max

~~~~
<xs:element name="age">
  <xs:simpleType>
    <xs:restriction base="xs:integer">
      <xs:minInclusive value="0"/>
      <xs:maxInclusive value="120"/>
    </xs:restriction>
  </xs:simpleType>
</xs:element> 
~~~~

### Enumeration

~~~~
<xs:element name="car" type="carType"/>

<xs:simpleType name="carType">
  <xs:restriction base="xs:string">
    <xs:enumeration value="Audi"/>
    <xs:enumeration value="Golf"/>
    <xs:enumeration value="BMW"/>
  </xs:restriction>
</xs:simpleType>
~~~~

### Pattern

- regexp

~~~~
<xs:restriction base="xs:string">
  <xs:pattern value="([a-z])+"/>
</xs:restriction>
~~~~

### WhiteSpace
- preserve: keep whitespaces
- replace: replace whitespace characters with spaces
- collapse: collapse all whitespace characters to a single space

~~~~
<xs:restriction base="xs:string">
  <xs:whiteSpace value="preserve"/>
</xs:restriction>
~~~~

<br />

## Complex Elements

- empty elements
- elements that contain only other elements
- elements that contain only text
- elements that contain both other elements and text

### Complex Example
~~~~
<xs:element name="employee" type="personinfo"/>
<xs:element name="student" type="personinfo"/>

<xs:complexType name="personinfo">
  <xs:sequence>
    <xs:element name="firstname" type="xs:string"/>
    <xs:element name="lastname" type="xs:string"/>
  </xs:sequence>
</xs:complexType>

<xs:element name="professor" type="fullpersoninfo">

<xs:complexType name="fullpersoninfo">
  <xs:complexContent>
    <xs:extension base="personinfo">
      <xs:sequence>
        <xs:element name="address" type="xs:string"/>
        <xs:element name="city" type="xs:string"/>
        <xs:element name="country" type="xs:string"/>
      </xs:sequence>
    </xs:extension>
  </xs:complexContent>
</xs:complexType> 
~~~~

### Empty Element
~~~~
<xs:complexType name="prodtype">
  <xs:attribute name="prodid" type="xs:positiveInteger"/>
</xs:complexType>
~~~~

### Text only + attribute

~~~~
<xs:complexType name="shoetype">
  <xs:simpleContent>
    <xs:extension base="xs:integer">
      <xs:attribute name="country" type="xs:string" />
    </xs:extension>
  </xs:simpleContent>
</xs:complexType>
~~~~

<br />

## Element Indicators

- All - any order, only once
- Choice - order, at most once
- Sequence - order, only once

- minOccurs
- maxOccurs

<br />

## Data Types

### String

- xs:string

### Date

| Name          | Description   |
| ------------- |-------------:|
| xs:date      | YYYY-MM-DD |
| xs:dateTime     | YYYY-MM-DDThh:mm:ss      |
| xs:duration | PnYnMnDTnHnMnS |
| xs:gDay | DD      |
| xs:gMonth | MM      |
| xs:gMonthDay | MM-DD      |
| xs:gYear | YYYY      |
| xs:gYearMonth | YYYY-MM      |
| xs:time | hh:mm:ss      |


### Numeric

- xs:byte
- xs:decimal
- xs:int
- xs:integer
- xs:long
- xs:negativeInteger
- xs:nonNegativeInteger
- xs:nonPositiveInteger
- xs:positiveInteger
- xs:short
- xs:unsignedLong
- xs:unsignedInt
- xs:unsignedShort
- xs:unsignedByte
- xs:float
- xs:double

### Boolean

- xs:boolean