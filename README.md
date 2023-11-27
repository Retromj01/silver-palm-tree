carpet

# Release Action properties for Curseforge and Snapshots
	# The Curseforge versions "names" or ids for the main branch (comma separated: 1.16.4,1.16.5)
	# This is needed because CF uses too vague names for prereleases and release candidates
	# Can also be the version ID directly coming from https://minecraft.curseforge.com/api/game/versions?token=[API_TOKEN]
	release-curse-versions = Minecraft 1.20:1.20.3-Snapshot
	# Whether or not to build another branch on release
	release-extra-branch = false
	# The name of the second branch to release
	release-extra-branch-name = 1.20.2
	# The "name" or id of the Curseforge version for the secondary branch
	# This is needed because CF uses too vague names for snapshots
	# Can also be the version ID directly coming from https://minecraft.curseforge.com/api/game/versions?token=[API_TOKEN]
	release-extra-curse-version = Minecraft 1.20:1.20.2
