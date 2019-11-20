# Mra Examples

This repo contains a couple of scripts to help convert the .ini or Bruno's bat files into the new MRA format. The script is pretty good, but doesn't work perfectly.

To try this out, look inside the arcade directory. This has another readme, and should have enough files to get started.


## MRA Format

```xml
<misterromdescription>
  <rbf>DonkeyKong</rbf>
  <rom index="0" zip="dkong.zip" md5="05fb1dd1ce6a786c538275d5776b1db1">
        <part name="c-2j.bpr"/>
        <part zip="another.zip" name="v-5e.bpr"/>
		<part repeat="3328" >00</part>
		<part>
 80 80 80 80 80 80 7f 7f 7f 7f 7f 7f 7f 80 80 80
</part>
	</rom>
</misterromdescripton>

```
