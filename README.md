at this timei should handle the 'cannot VACUUM from within a transaction' errror in the 151 line, googd luck
now i found another problem , The importer couldn't map "emissions to air" → "air", so it dropped ALL biosphere flows.
it seems manually i should change the exchanges name to me matchable with biosphere 3.0. i dot  know how.


otoday i found another interesting thing, it seems : XML files are ecospold v1 format, but they're from openLCA ( generator="openLCA"), which creates slightly different XML that doesn't pass the strict schema validation in the pyecospold library.
