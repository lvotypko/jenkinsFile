properties(
    [
        pipelineTriggers(
            [[
                $class: 'CIBuildTrigger', checks: [[expectedValue: 'rpms', field: '$.commit.namespace']], providerName: 'fedmsg', selector: 'topic = "org.fedoraproject.prod.git.receive"'
            ]]
        )
    ]
)
node(){
  echo 'hello'
}
