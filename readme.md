# 🛒 E-Commerce Database Design – Peer Assignment

## 🧱 Team Members
- [Thapelo Makgakga]


## 📐 ERD (Entity-Relationship Diagram)
the erd diagram inside an pdf document called, erd.pdf

## 🗃️ Tables Overview

| Table Name | Description |
|------------|-------------|
| `brand` | Stores brand info |
| `product_category` | Classifies products |
| `product` | Basic product data |
| `product_item` | Individual sellable items |
| `product_image` | Image URLs per item |
| `color` | Available colors |
| `product_variation` | Variation combinations |
| `size_category` | E.g. Clothing or Shoe sizes |
| `size_option` | S, M, L, 38, 42 etc. |
| `product_attribute` | Material, weight, etc. |
| `attribute_category` | Technical, physical etc. |
| `attribute_type` | Data types (text, boolean, etc.) |

## 🔄 Data Flow
- A product has many items (variations)
- Items can have images, attributes, sizes, and colors
- Attributes use categories and types for organization

## 💾 Database File
Find the SQL schema under `/schema/ecommerce.sql`

## 👥 Collaboration
We used GitHub for version control and collaboration. Every member contributed to:
- Table design
- ERD logic
- SQL scripting
- Documentation




