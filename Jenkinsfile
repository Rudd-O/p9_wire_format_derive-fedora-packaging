// https://github.com/Rudd-O/shared-jenkins-libraries
@Library('shared-jenkins-libraries@master') _


genericFedoraRPMPipeline(
	{
        downloadCrateSourceFromSpecfile sha256sum: "e6085210d8ec9bcbdf38b5c8e97bccef1877f3f291eae48b65388ca979f5314e"
	},
	{
		SRPMStrategyRpmbuildBs()()
	},
)
