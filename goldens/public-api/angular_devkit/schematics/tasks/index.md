## API Report File for "@angular-devkit/schematics_tasks"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { JsonObject } from '@angular-devkit/core';

// @public (undocumented)
export class NodePackageInstallTask implements TaskConfigurationGenerator<NodePackageTaskOptions> {
    constructor(workingDirectory?: string);
    constructor(options: NodePackageInstallTaskOptions);
    // (undocumented)
    hideOutput: boolean;
    // (undocumented)
    packageManager?: string;
    // (undocumented)
    packageName?: string;
    // (undocumented)
    quiet: boolean;
    // (undocumented)
    toConfiguration(): TaskConfiguration<NodePackageTaskOptions>;
    // (undocumented)
    workingDirectory?: string;
}

// @public (undocumented)
export class NodePackageLinkTask implements TaskConfigurationGenerator<NodePackageTaskOptions> {
    constructor(packageName?: string | undefined, workingDirectory?: string | undefined);
    // (undocumented)
    packageName?: string | undefined;
    // (undocumented)
    quiet: boolean;
    // (undocumented)
    toConfiguration(): TaskConfiguration<NodePackageTaskOptions>;
    // (undocumented)
    workingDirectory?: string | undefined;
}

// @public (undocumented)
export class RepositoryInitializerTask implements TaskConfigurationGenerator<RepositoryInitializerTaskOptions> {
    constructor(workingDirectory?: string | undefined, commitOptions?: CommitOptions | undefined);
    // (undocumented)
    commitOptions?: CommitOptions | undefined;
    // (undocumented)
    toConfiguration(): TaskConfiguration<RepositoryInitializerTaskOptions>;
    // (undocumented)
    workingDirectory?: string | undefined;
}

// @public (undocumented)
export class RunSchematicTask<T> implements TaskConfigurationGenerator<RunSchematicTaskOptions<T>> {
    constructor(s: string, o: T);
    constructor(c: string, s: string, o: T);
    // (undocumented)
    protected _collection: string | null;
    // (undocumented)
    protected _options: T;
    // (undocumented)
    protected _schematic: string;
    // (undocumented)
    toConfiguration(): TaskConfiguration<RunSchematicTaskOptions<T>>;
}

// @public @deprecated (undocumented)
export class TslintFixTask implements TaskConfigurationGenerator<TslintFixTaskOptions> {
    constructor(config: JsonObject, options: TslintFixTaskOptionsBase);
    constructor(options: TslintFixTaskOptionsBase);
    constructor(path: string, options: TslintFixTaskOptionsBase);
    // (undocumented)
    protected _configOrPath: null | string | JsonObject;
    // (undocumented)
    protected _options: TslintFixTaskOptionsBase;
    // (undocumented)
    toConfiguration(): TaskConfiguration<TslintFixTaskOptions>;
}

// (No @packageDocumentation comment for this package)

```
