# rules-us-va

Virginia rules encoded in Akoma Ntoso XML format for the Cosilico rules-as-code ecosystem.

## Structure

```
rules-us-va/
├── statutes/                    # Code of Virginia
│   ├── title-58.1-taxation/     # Title 58.1 - Taxation
│   └── title-63.2-welfare/      # Title 63.2 - Welfare (Social Services)
└── regulations/                 # Virginia Administrative Code (VAC)
```

## Sources

- **Code of Virginia**: https://law.lis.virginia.gov/vacode/
- **Virginia Administrative Code**: https://law.lis.virginia.gov/admincode/

## Format

All rules are encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML, an OASIS standard for legal documents.

## Related Repositories

- [rac](https://github.com/CosilicoAI/rac) - Core DSL engine
- [rac-us](https://github.com/CosilicoAI/rac-us) - US federal rules
- [arch](https://github.com/CosilicoAI/arch) - Source document archive

## License

The underlying Virginia statutes and regulations are public domain. The Akoma Ntoso encodings in this repository are released under the MIT License.
